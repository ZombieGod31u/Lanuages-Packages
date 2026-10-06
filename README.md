# PolyLingo Language Packages

Official language packages for PolyLingo.

Packages are digitally signed using Ed25519.

Each package consists of:

- The language package ZIP.
- A corresponding `.sig` signature file.

PolyLingo verifies the package signature before installing the package.

## Package Structure

```text
Language/
└── Version/
    ├── Language.zip
    └── Language.zip.sig