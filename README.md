# amplify-astro-cicd

Minimal Astro site for Amplify staging PR previews and GitHub CI.

Walkthrough: https://amplify-astro-cicd-walkthrough.johna.kiwi/

## Local

```bash
npm install
npm run dev
```

## Branches

- `main` - production Amplify branch
- `staging` - pre-production Amplify branch

Feature PRs target `staging` first. See the walkthrough for Amplify Console setup.

## Build

Amplify uses [`amplify.yml`](amplify.yml). Non-`main` builds write a disallow-all `robots.txt`.
