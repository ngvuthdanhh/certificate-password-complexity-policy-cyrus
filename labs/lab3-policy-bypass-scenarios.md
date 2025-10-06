# Lab 3 – Policy Bypass Scenarios

## Objective
Explore how attackers attempt to bypass or weaken complexity policies.

## Steps
1. Test policy enforcement on different entry points:
   - GUI login
   - Remote SSH
   - Password reset function
2. Attempt password resets with weaker patterns.
3. Simulate “password spraying” with common complex-looking patterns (e.g., `Winter2025!`).

## Expected Outcome
- Policy should be consistent across all entry points.
- Any bypass is a critical misconfiguration.

## Reflection
Consistency is key. Many breaches occur because policies are enforced in some places but not others.
