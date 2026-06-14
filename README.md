# Contemporary Display

Contemporary Display is a variable font with a single weight (`wght`) axis, ranging
from Regular (400) to Black (900). It is derived from the
[Inter](https://github.com/rsms/inter) typeface and licensed under the
[SIL Open Font License 1.1](OFL.txt).

![Sample](documentation/ContemporaryDisplay-sample.png)

## Building

Source files live in [`sources/`](sources). Build the binaries with
[gftools](https://github.com/googlefonts/gftools):

```
gftools builder sources/config.yaml
```

Built fonts are written to [`fonts/`](fonts).

## Repository structure

This repository follows the
[Google Fonts upstream layout](https://googlefonts.github.io/gf-guide/index):

```
.
├── AUTHORS.txt
├── CONTRIBUTORS.txt
├── OFL.txt
├── README.md
├── documentation/          # specimen images used on the catalog
├── fonts/
│   ├── variable/
│   │   └── ContemporaryDisplay[wght].ttf   # submit this one to Google Fonts
│   ├── otf/
│   │   └── ContemporaryDisplay[wght].otf
│   └── webfonts/
│       └── ContemporaryDisplay[wght].woff2
└── sources/                # editable source files (.glyphs / .glyphspackage / .ufo)
```

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
See [OFL.txt](OFL.txt). It is available with a FAQ at https://openfontlicense.org
