# benjaminkasper.dev – Personal Website

[![Deploy to Server](https://github.com/TwilightWarden1001/Personal-Website/actions/workflows/deploy.yml/badge.svg)](https://github.com/TwilightWarden1001/Personal-Website/actions)
![SSL Status](https://img.shields.io/website-up-down-green-red/https/benjaminkasper.dev.svg?label=SSL)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fbenjaminkasper.dev)
[![W3C Validation](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fbenjaminkasper.dev)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbenjaminkasper.dev)

This is the source code for my personal website, hosted at [benjaminkasper.dev](https://benjaminkasper.dev). The site is deployed on a DigitalOcean Ubuntu VPS and automatically updated using GitHub Actions. It serves as a simple, secure, and fast portfolio presence.

## Live Site
**URL:** [https://benjaminkasper.dev](https://benjaminkasper.dev)

## Tech Stack
- HTML/CSS (static content)
- NGINX (web server)
- GitHub Actions (CI/CD)
- Certbot + Let's Encrypt (HTTPS)
- DigitalOcean (VPS)
- UFW + Fail2Ban (basic server hardening)

## Deployment
Commits pushed to the `main` branch trigger automatic deployment using a secure GitHub Actions workflow over SSH.

## Security
- Key-based SSH only
- UFW restricts access to SSH and HTTPS
- Fail2Ban prevents SSH brute-force attempts

## Future Improvements
- Add project portfolio section
- Implement blog with markdown support
- Add dark mode toggle

## Credits
- [appleboy/ssh-action](https://github.com/appleboy/ssh-action) – GitHub SSH deployment
- [Let’s Encrypt](https://letsencrypt.org) – Free SSL
- [DigitalOcean](https://digitalocean.com) – VPS hosting