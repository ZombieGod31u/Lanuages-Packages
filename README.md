# PolyLingo Language Packages

This repository distributes encrypted, signed language packages, tools, language-specific tool patches, and individually downloadable books.

```text
Languages/<language>/<version>/<package>.pkg.enc
Tools/<tool>/<version>/<package>.pkg.enc
Tools/<tool>/Patches/<language>/<version>/<package>.pkg.enc
Tools/Books/<book-id>/Patches/<language>/<version>/<package>.pkg.enc
```

Each encrypted package has a matching `.sig` file. The current tree keeps the newest version of each package family; older versions remain in Git history. Book identifiers remain unchanged when their folders move. The updated app discovers books in `Tools/Books`; older app builds that only recognize the former layout need an update to download them.
