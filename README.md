### SDsimulator
System Dynamics Interface (UKRI Interdisciplinary Centre for Circular Chemical Economy)

#### First build with new version `.mdl` model:

Firstly backup `/config`, `packages/app/index.html`, `packages/app/package.json`, `packages/app/src/graph-view.ts`, `packages/app/src/index.css` and `packages/app/src/index.js`.

Make sure backup `package-lock.json` and `package.json` both.

Remember only `sdms.mdl` in the project root folder.

```bash
npm create @sdeverywhere@latest
```

**Replace all backup files.**

```bash
npm install chartjs-plugin-zoom@0.7.7
```

```bash
npm run dev
```

#### How to build in the new localhost:

```bash
npm install -g @sdeverywhere/cli
```

```bash
sde --version
```

```bash
npm install @sdeverywhere/plugin-check
```

```bash
npm run dev
```
