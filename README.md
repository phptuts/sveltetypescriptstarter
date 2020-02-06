# Typescript template for Svelte v3

## Setup

```
npm install -g degit
degit github:phptuts/sveltetypescriptstarter my-app
cd my-app
cp .env-template ./src/env.ts
npm install
npm run dev
```

All environment variables are stored in ./src/env.ts file.  This is ignored by github.  I recommend that you only have one .env file to keep things simple.

## Typescript on components

This is required for visual code.

```typescript
<script lang="typescript"></script>
```
