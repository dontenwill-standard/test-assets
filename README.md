# test-assets

Öffentliches Distributions-Repository für Test-Tools, Packages und Assets von Dontenwill AG.

## Packages

| Package | Technologie | Beschreibung |
|---------|-------------|--------------|
| `@dontenwill-standard/be-portal-playwright-helpers` | npm | Playwright-Helper-Klassen für be-portal GUI-Tests |

## Installation

Alle Packages werden über GitHub Packages veröffentlicht. GitHub Packages erfordert immer eine Authentifizierung, auch für öffentliche Packages.

Erstelle einen GitHub Personal Access Token (classic) mit dem Scope `read:packages` und setze ihn als Umgebungsvariable:

```bash
export DONTENWILL_PACKAGES_READ_TOKEN=ghp_...
```

### npm

Füge folgendes in die `.npmrc` deines Projekts ein (neben der `package.json`):

```
@dontenwill-standard:registry=https://npm.pkg.github.com
//npm.pkg.github.com/:_authToken=${DONTENWILL_PACKAGES_READ_TOKEN}
```

Anschließend das Package installieren:

```bash
npm install @dontenwill-standard/be-portal-playwright-helpers
```
