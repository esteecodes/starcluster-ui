# StarCluster UI

Astro-first UI components.

## Install

```bash
npm install starcluster-ui
```

## Usage

### Named import

```astro
---
import { ScButton } from "starcluster-ui";
---

<ScButton variant="primary" outline pill elevated size="small">
  Button
</ScButton>
```

### Direct path import

```astro
---
import ScButton from "starcluster-ui/ScButton.astro";
---

<ScButton variant="neutral">Hello</ScButton>
```

## Status

Early minimal release to establish the package name and public API.
