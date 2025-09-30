
---

## Results — Password Strength Tests

| # | Password (example) | Tool Used | Score / Rating | Feedback Summary | Screenshot |
|---|---------------------|-----------|---------------|------------------|------------|
| 1 | password123 | passwordmeter.com | Weak | Common word, predictable pattern | `screenshots/01-password123.png` |
| 2 | qwerty2020 | passwordmeter.com | Weak | Sequential pattern, easy to guess | `screenshots/02-qwerty2020.png` |
| 3 | Passw0rd! | passwordmeter.com | Medium | Better with mix, still common pattern | `screenshots/03-Passw0rd!.png` |
| 4 | Summer2024# | passwordmeter.com | Medium | Includes year, predictable | `screenshots/04-Summer2024#.png` |
| 5 | B1ueCar! | passwordmeter.com | Medium | Short, but uses substitution | `screenshots/05-B1ueCar!.png` |
| 6 | S!mpl3P@ss | passwordmeter.com | Medium-Strong | Mix of cases, symbols, numbers | `screenshots/06-Simpl3P@ss.png` |
| 7 | horse-battery-staple | passwordmeter.com | Strong | Long passphrase, easy to remember | `screenshots/07-horse-battery-staple.png` |
| 8 | correct-horse-battery-staple-42 | passwordmeter.com | Very Strong | Very long, high entropy, memorable | `screenshots/08-correct-horse.png` |
| 9 | M@tr!x_2025#Secure | passwordmeter.com | Strong | Long, symbols, mixed cases | `screenshots/09-Matrix2025.png` |
|10 | 7R&9x!kL#y2z | passwordmeter.com | Strong | Random characters, hard to guess | `screenshots/10-random.png` |

*(Replace with your real scores & screenshots.)*

---

## Analysis
- **Length matters most**: passwords with 16+ characters scored significantly higher.
- **Randomness increases entropy**: fully random strings were strong, though harder to memorize.
- **Passphrases are effective**: long, easy-to-remember word combinations scored as strong or very strong.
- **Common patterns weaken strength**: passwords containing dictionary words, years, or predictable substitutions (e.g., `Passw0rd`) scored poorly.
- **Symbols and case variety help**: adding mixed case, numbers, and symbols raised the score, but not as much as simply increasing length.

---

## Best Practices for Strong Passwords
1. Use a **minimum length of 12–16 characters**.
2. Prefer **passphrases** over short complex strings (e.g., `BlueSky!Tiger#2025`).
3. Mix **uppercase, lowercase, numbers, and symbols**.
4. Avoid **dictionary words, names, dates, or common substitutions**.
5. Use a **password manager** to generate and store unique passwords.
6. Enable **Multi-Factor Authentication (MFA)** wherever possible.

---

## Common Password Attacks
- **Brute-force attack**: tries every possible combination; countered by length + complexity.
- **Dictionary attack**: uses wordlists of common passwords; countered by avoiding common words.
- **Rainbow tables**: precomputed hash lookups; countered by salting and strong hashing algorithms.
- **Credential stuffing**: reusing stolen credentials from breaches; countered by unique passwords.
- **Phishing/social engineering**: tricking users into revealing passwords; countered by user awareness + MFA.

---

## References
- [Password Meter](https://passwordmeter.com)  
- [OWASP Authentication Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)  
- NIST Password Guidelines (SP 800-63B)  
