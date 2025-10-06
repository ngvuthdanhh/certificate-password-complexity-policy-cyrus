# Lab 1 – Basic Password Complexity Policy Setup

## Objective
Set up a minimum viable password complexity policy and test it on a demo environment.

## Steps
1. Define basic requirements:
   - Minimum length: 8
   - Must include uppercase, lowercase, and numbers.
2. Apply these rules in a test system (e.g., Linux PAM or Windows Local Security Policy).
3. Attempt to create user accounts with different password patterns.

## Expected Outcome
- Weak passwords like `password` or `12345678` should be rejected.
- Stronger ones like `Secure123` should be accepted.

## Reflection
This lab highlights how baseline rules already prevent trivial attacks, but still leave gaps against brute force or dictionary attacks.
