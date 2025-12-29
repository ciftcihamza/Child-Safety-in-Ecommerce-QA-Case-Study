# Exploratory Findings – Child Safety in E-Commerce

## EF-01 – One-Tap Purchase Risk on Shared Devices

During exploratory testing from a child perspective, it was observed that a purchase can be completed with a single tap when address and payment information are saved.

No additional verification (password, PIN, or biometric confirmation) is required before completing the transaction.

### Risk Observation
This behavior increases the risk of unauthorized or accidental purchases by children using shared family devices.

### Test Approach
- Exploratory manual testing
- Child-user mindset
- Shared device scenario

## EF-02 – No Configurable Purchase Protection for Child Safety

During exploratory testing, no configurable option was found to enforce additional verification before completing a purchase on shared devices.

There is no visible setting allowing parents to enable mandatory password, PIN, or biometric confirmation specifically for purchase actions.

### Risk Observation
Parents have no control mechanism to prevent accidental or unauthorized purchases made by children on shared family devices.

### Test Approach
- Exploratory manual testing
- Settings and account configuration review
- Child and parent combined perspective
