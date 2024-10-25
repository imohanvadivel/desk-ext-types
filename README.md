# Zoho Desk Extensions Types

This repository contains typescript type definition for authoring Zoho Desk extension.

## Usage

1. Installation

```bash
npm i --save-dev desk-ext-types
```

2. Configure tsconfig.json

```json
{
    "compilerOptions": {
        "typeRoots": ["./node_modules/@types", "./node_modules/desk-ext-types"]
    }
}
```

The configuration above tells the TypeScript compiler to look for type definitions in both `./node_modules/@types` and `./node_modules/desk-ext-type`. Usually, most external type definitions come from [Definitely Typed](https://github.com/DefinitelyTyped/DefinitelyTyped) and are stored in `/@types`, which TypeScript includes automatically. However, since we keep the extension types separately, they’re installed in `/desk-ext-types` instead.

This setup makes the types globally available without needing import statements, as the extension SDK is part of the main environment rather than a package that the extension itself includes.

#### Also checkout

-   [Deskblocks](https://deskblocks.mohanvadivel.com)
-   [Zoho Desk Extension SDK Documentation](https://www.zoho.com/desk/extensions/guide/)
-   [Extension developer forum](https://help.zoho.com/portal/en/community/zoho-desk/zoho-desk-extension-developers)
