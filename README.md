<h1 align="center">AetherKnife</h1>

<p align="center"><em>A modern dark-grey and neon-purple reskin, delivered as a hosted external stylesheet.</em></p>

<p align="center">
  <img alt="Type" src="https://img.shields.io/badge/Type-Stylesheet-3B82F6?style=for-the-badge">
  <img alt="CSS" src="https://img.shields.io/badge/CSS-Custom%20Properties-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img alt="Delivery" src="https://img.shields.io/badge/Delivery-GitHub%20Pages-181717?style=for-the-badge&logo=github&logoColor=white">
</p>

---

## Overview

AetherKnife is a dark-grey reskin with neon-purple accents, published as a single
stylesheet through GitHub Pages so it can be loaded by a plain browser `<link>`.

Rather than fighting the host site's large core stylesheet, it overrides the same
CSS custom properties the site's own theme packs define. The result stacks cleanly
on top of the existing dark theme instead of competing with it.

## Features

- Dark-grey base palette with neon-purple accents.
- Driven entirely by custom properties, so re-colouring is a single edit.
- Layers on top of the host theme rather than replacing it.
- Published automatically on every push to `main`.

## Install

1. Open your profile **Settings** on the target site.
2. Leave the theme set to its standard dark option.
3. Paste the published stylesheet URL into the **External CSS Stylesheet** field
   (the one described as stacking on top of the selected theme).
4. Save, then hard-refresh.

## Customising

Every colour is defined in the token block at the top of `aetherknife.css`
(`--ak-bg-0` … `--ak-bg-6`, `--ak-text*`, `--ak-accent`, `--ak-teal`). The rest of
the file only references those tokens, so changing them re-themes the whole sheet.

## Deployment

GitHub Pages is configured to publish `aetherknife.css` on every push to `main`. The repository is private, but Pages visibility is set to public so the
stylesheet can be fetched without a login.
