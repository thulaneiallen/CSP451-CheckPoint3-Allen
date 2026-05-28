# CSP-451 CheckPoint 3

![CI](https://github.com/thulaneiallen/CSP451-CheckPoint3-Allen/actions/workflows/ci.yml/badge.svg?branch=main)
![CodeQL](https://github.com/thulaneiallen/CSP451-CheckPoint3-Allen/actions/workflows/codeql.yml/badge.svg?branch=main)

This project is a small Node.js and Express HTTP service for CSP-451 CheckPoint 3. It demonstrates GitHub Actions CI, automated testing, coverage gates, npm audit checks, CodeQL scanning, Dependabot configuration, and branch protection.

## Endpoints

- `GET /` returns a basic JSON status response.
- `GET /health` will be added on a feature branch.

## Local Commands

```bash
npm ci
npm run format:check
npm run lint
npm test
npm run audit:check
npm start
```
