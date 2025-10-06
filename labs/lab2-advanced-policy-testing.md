# Lab 2 – Advanced Password Policy Testing

## Objective
Strengthen policy with symbols, longer length, and prevention of common dictionary words.

## Steps
1. Update rules:
   - Minimum length: 12
   - At least 1 special character (!@#$%^&*).
   - Disallow passwords from a dictionary file.
2. Test different candidate passwords.
3. Run a dictionary-based attack simulation with Hydra/John (demo only).

## Expected Outcome
- Dictionary passwords (`Summer2024!`) should be rejected.
- Random high-entropy strings like `M9&dRt4$z1Qp` should pass.

## Reflection
Complexity rules must balance usability with security. Overly strict policies may cause users to write passwords down.
