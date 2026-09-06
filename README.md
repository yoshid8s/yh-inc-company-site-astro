# Y&H Inc. Company Site

Official company website for Y&H Inc.

Production site: https://yh-inc.jp/en/

## Brand Integrity by Design

Y&H explores Brand Integrity through two complementary dimensions:

- Behavioral Integrity
- Data Integrity

The site presents Y&H's research and practical exploration of:

- Brand Integrity Index
- One Page × One Advertiser
- Agentic Advertising
- Originator Profile and C2PA as examples of technologies supporting Data Integrity

## Tech Stack

- Astro
- TypeScript
- pnpm
- Static HTML/CSS
- Sakura Internet

## Development

Install dependencies:

    pnpm install

Start the local development server:

    pnpm dev

Local development URL:

    http://localhost:4321/

## Build

Create a production build:

    pnpm build

Production files are generated in:

    dist/

The production site consists primarily of:

    dist/
    ├── _astro/
    ├── en/
    │   └── index.html
    ├── images/
    ├── index.html
    └── yh-logo.svg

The root page redirects to:

    /en/

## Production

Production URL:

    https://yh-inc.jp/en/

Hosting:

    Sakura Internet

The Astro site is deployed to:

    /home/yh-inc/www/

Existing subdirectories used by other websites and services must not be deleted or overwritten during deployment.

## GitHub Actions

Pushes and pull requests to `main` run a production build automatically.

The workflow verifies:

1. Repository checkout
2. pnpm setup
3. Node.js setup
4. Dependency installation
5. Astro production build

## Collaboration

Brand Integrity research and discussion:

https://github.com/yoshid8s/brand-integrity
