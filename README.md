# GID Digital Card

This repository contains the configuration for your GID digital card. Your profile is powered by the `config.json` file in this repository.

## How to Use

1. **Edit `config.json`:** Fill in your details, including your verification token.
2. **Push Changes:** Commit and push your changes to this repository.
3. **Sync Profile:** Visit the GID Sync page and submit your GitHub username to update your live profile.

## Files

- `config.json`: Contains your profile details.
- `README.md`: This file, describing the repository purpose.

## Notes


## Delete Profile

If you want to remove your profile from GID, replace `config.json` with:

```json
{ "delete": true }
```

Then trigger sync once. The backend will delete all stored profile information for your GitHub account.