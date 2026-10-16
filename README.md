# Personal report

Password-encrypted personal report for GitHub Pages.

Only the encrypted payload and the unlock screen are stored here. Source documents and the access password are not included.

Encryption: AES-256-GCM with PBKDF2-SHA-256 (600,000 iterations), random salt and IV. Decryption happens in the browser over HTTPS. A strong independent access password is required; it is not a GitHub account password.
