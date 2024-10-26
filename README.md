# Zoho Desk Extensions Types

This repository contains typescript type definition for authoring Zoho Desk extension.

## Usage

1. Installation

```bash
npm i --save-dev desk-ext-types
```

2. Include the reference in main.ts

```ts
/// <reference types="desk-ext-types" />
```

With this setup, the types are made globally accessible without requiring any import statements, since the extension SDK is integrated into the main environment instead of being a package that the extension itself incorporates.

#### Also checkout

-   [Deskblocks](https://deskblocks.mohanvadivel.com)
-   [Zoho Desk Extension SDK Documentation](https://www.zoho.com/desk/extensions/guide/)
-   [Extension developer forum](https://help.zoho.com/portal/en/community/zoho-desk/zoho-desk-extension-developers)
