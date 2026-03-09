# Stackwright + Next.js Template (Pages Router)

Starter template for [Stackwright](https://github.com/Per-Aspera-LLC/stackwright) projects using Next.js Pages Router.

## Usage

This template is used automatically by the Stackwright CLI:

```bash
npx @stackwright/cli scaffold my-project
```

You can also use it directly via GitHub's "Use this template" button.

## What's included

- `pages/_app.tsx` — App root with Stackwright component registration
- `pages/index.ts` — Root page using `DynamicPage` with `getStaticProps`
- `pages/[slug].tsx` — Dynamic slug-based routing
- `next.config.js` — Pre-configured with `createStackwrightNextConfig()`
- `.vscode/settings.json` — YAML schema validation for Stackwright files
- `.env.local.example` — Debug flag configuration
- `.gitignore` — Next.js + Stackwright ignores

## Placeholders

The CLI replaces these placeholders during scaffolding:

- `{{projectName}}` — npm package name
- `{{siteTitle}}` — Site title for app bar and browser tab
- `{{year}}` — Current year for copyright notices

## After scaffolding

The CLI generates additional files via Zod schema introspection:

- `stackwright.yml` — Site configuration (theme, navigation, app bar, footer)
- `pages/content.yml` — Root page content
- `pages/getting-started/content.yml` — Getting started guide
- `package.json` — Dependencies and scripts
- `tsconfig.json` — TypeScript configuration
