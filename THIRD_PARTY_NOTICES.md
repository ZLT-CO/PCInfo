# Third-party notices

PCInfo bundles or depends on the following third-party components. Their
licenses are reproduced or referenced below.

## Runtime dependencies

| Component | Version | License | Use |
|-----------|---------|---------|-----|
| [PySide6 / Qt for Python](https://www.qt.io/qt-for-python) | 6.6+ | LGPL-3.0 (or commercial) | GUI framework. Distributed as the unmodified LGPL PySide6 wheels; PCInfo links dynamically. |
| [psutil](https://github.com/giampaolo/psutil) | 5.9+ | BSD-3-Clause | Cross-platform CPU, memory, disk, battery and network access. |
| [GPUtil](https://github.com/anderskm/gputil) | 1.4+ (optional) | MIT | Wrapper over `nvidia-smi` for NVIDIA GPU metrics. |

## Bundled assets

### Lucide icons (`src/pcinfo/assets/icons`, `src/pcinfo/assets/appicon.svg`)

- Source: <https://lucide.dev>
- License: **ISC License**

```text
ISC License

Copyright (c) for portions of Lucide are held by Cole Bemis 2013-2022 as part
of Feather (MIT). All other copyright (c) for Lucide are held by Lucide
Contributors 2022.

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR
OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
PERFORMANCE OF THIS SOFTWARE.
```

## Build-time only

| Component | License | Use |
|-----------|---------|-----|
| [PyInstaller](https://pyinstaller.org) | GPL-2.0 with a special exception | Produces standalone executables (build tool only; not linked into the app). Its exception explicitly permits packaging commercial/proprietary software. |
| [pytest](https://pytest.org), pytest-qt | MIT | Test tooling. |
