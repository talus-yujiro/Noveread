# Noveread

## Language

[English](/README.md)  
[Japanese](/README/README-ja.md)
[Chinese](/README/README-zh-CN.md)

## Overview

You can download novels from web novel services and read them using the reader.  
You can also read them directly on the web.  

By bookmarking the site, you can access it anytime.  

Enjoy your web novel life! 👋

## How to use

Download the latest executable file from the [Release](https://github.com/talus-yujiro/Noveread/releases) page.

| OS      | Distribution               | File Name            |
|---------|----------------------------|----------------------|
| Linux   | Debian, Ubuntu             | Noveread-*.deb       |
| Linux   | Other distributions        | Noveread-*.AppImage  |
| Windows | Windows 11 and earlier     | Noveread.setup.*.exe |

Alternatively, download the source code, and in the root folder after extraction, run:

```bash
npm run dist
```

(Make sure you have Node.js installed.)

An executable file should be created in the dist folder.

## Roadmap
- [x] v0.0.1 Basic startup achieved
- [ ] v0.5.0 Implement download processing
- [ ] v1.0.0 Make it usable as a full application

## Recent Changes

### 2025/07/01

- Updated `package.json`  
  - Added support for building `.deb` files for release

### 2025/06/27

- v1.0.0 released  
  - Basic startup achieved  
  - Experimental introduction of `webview`
