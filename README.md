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

- Ensure this repository is public.
- Do not add extra files or folders, as they may cause validation to fail.
- Repository name must be `GID-digitalcard`.
- `config.json` must use strict fields only: `verify`, `first_name`, `last_name`, `title`, `bio`, `location`, `email`, `website`, `social`, `skills`, `certifications`, `pgp_key`.
- `social` accepts `github`, optional `linkedin`, optional `x`.
- `skills` allows up to 10 items, and `certifications` allows up to 5 items.