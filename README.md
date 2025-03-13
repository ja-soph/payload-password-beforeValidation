# payload-password-beforeValidation

## Reproduction

- Execute docker compose to test the bug
- Start dev via npm run dev
- Go to admin panel
- Try to add a User with a password that has either less than 6 characters or no upper/lower case letters
