# 👷 `Cloudflare Assets Worker`

## Digital Cloud assets on Google Cloud Storage

[g-assets.ss-o.workers.dev](https://g-assets.ss-o.workers.dev)

### Tree

```
 ── img
    ├── assets
    │   ├── brands
    │   │   ├── ethereum
    │   │   │   ├── ethereum-eth-logo-animated.gif
    │   │   │   ├── ethereum-eth-logo-full-horizontal.svg
    │   │   │   ├── ethereum-eth-logo-full-vertical.svg
    │   │   │   ├── ethereum-eth-logo.png
    │   │   │   └── ethereum-eth-logo.svg
    │   │   └── ipfs
    │   │       └── 1024x1024.png
    │   └── photo
    │       ├── code-2.jpg
    │       ├── code-3.jpg
    │       ├── code.jpg
    │       └── pic.jpg
    ├── digitalclouds
    │   ├── Archived
    │   │   ├── Blue_Digital Clouds.zip
    │   │   ├── Blue_Preview.zip
    │   │   ├── Green_Digital Clouds.zip
    │   │   ├── Green_Favicon.zip
    │   │   └── Green_Preview.zip
    │   ├── archives
    │   │   ├── blue_dc_logo.zip
    │   │   ├── green_dc_favicon.zip
    │   │   └── green_dc_logo.zip
    │   ├── blue-dc
    │   │   ├── __MACOSX
    │   │   │   └── JPG
    │   │   ├── v1
    │   │   │   ├── dc-b.jpg
    │   │   │   └── dc-b.png
    │   │   └── v2
    │   │       ├── dc-b.jpg
    │   │       └── dc-b.png
    │   ├── favicon
    │   │   ├── 1
    │   │   │   ├── android-icon-144x144.png
    │   │   │   ├── android-icon-192x192.png
    │   │   │   ├── android-icon-36x36.png
    │   │   │   ├── android-icon-48x48.png
    │   │   │   ├── android-icon-72x72.png
    │   │   │   ├── android-icon-96x96.png
    │   │   │   ├── apple-icon-114x114.png
    │   │   │   ├── apple-icon-120x120.png
    │   │   │   ├── apple-icon-144x144.png
    │   │   │   ├── apple-icon-152x152.png
    │   │   │   ├── apple-icon-180x180.png
    │   │   │   ├── apple-icon-57x57.png
    │   │   │   ├── apple-icon-60x60.png
    │   │   │   ├── apple-icon-72x72.png
    │   │   │   ├── apple-icon-76x76.png
    │   │   │   ├── apple-icon.png
    │   │   │   ├── apple-icon-precomposed.png
    │   │   │   ├── browserconfig.xml
    │   │   │   ├── favicon-16x16.png
    │   │   │   ├── favicon-32x32.png
    │   │   │   ├── favicon-96x96.png
    │   │   │   ├── favicon.ico
    │   │   │   ├── manifest.json
    │   │   │   ├── ms-icon-144x144.png
    │   │   │   ├── ms-icon-150x150.png
    │   │   │   ├── ms-icon-310x310.png
    │   │   │   └── ms-icon-70x70.png
    │   │   ├── 2
    │   │   │   ├── android-icon-144x144.png
    │   │   │   ├── android-icon-192x192.png
    │   │   │   ├── android-icon-36x36.png
    │   │   │   ├── android-icon-48x48.png
    │   │   │   ├── android-icon-72x72.png
    │   │   │   ├── android-icon-96x96.png
    │   │   │   ├── apple-icon-114x114.png
    │   │   │   ├── apple-icon-120x120.png
    │   │   │   ├── apple-icon-144x144.png
    │   │   │   ├── apple-icon-152x152.png
    │   │   │   ├── apple-icon-180x180.png
    │   │   │   ├── apple-icon-57x57.png
    │   │   │   ├── apple-icon-60x60.png
    │   │   │   ├── apple-icon-72x72.png
    │   │   │   ├── apple-icon-76x76.png
    │   │   │   ├── apple-icon.png
    │   │   │   ├── apple-icon-precomposed.png
    │   │   │   ├── browserconfig.xml
    │   │   │   ├── favicon-16x16.png
    │   │   │   ├── favicon-32x32.png
    │   │   │   ├── favicon-96x96.png
    │   │   │   ├── favicon.ico
    │   │   │   ├── manifest.json
    │   │   │   ├── ms-icon-144x144.png
    │   │   │   ├── ms-icon-150x150.png
    │   │   │   ├── ms-icon-310x310.png
    │   │   │   └── ms-icon-70x70.png
    │   │   └── __MACOSX
    │   │       ├── favicon
    │   │       │   ├── 1
    │   │       │   └── 2
    │   │       └── jpg
    │   ├── green-dc
    │   │   ├── __MACOSX
    │   │   │   ├── favicon2.ico
    │   │   │   ├── favicon.ico
    │   │   │   └── JPG
    │   │   ├── v1
    │   │   │   ├── dc-g
    │   │   │   │   ├── 1250x417.png
    │   │   │   │   ├── 2500x833.png
    │   │   │   │   ├── 5000x1667.png
    │   │   │   │   ├── dc-g.jpg
    │   │   │   │   └── dc-g.png
    │   │   │   ├── dc-g-preview.jpg
    │   │   │   └── favicon.ico
    │   │   │       ├── android-icon-144x144.png
    │   │   │       ├── android-icon-192x192.png
    │   │   │       ├── android-icon-36x36.png
    │   │   │       ├── android-icon-48x48.png
    │   │   │       ├── android-icon-72x72.png
    │   │   │       ├── android-icon-96x96.png
    │   │   │       ├── apple-icon-114x114.png
    │   │   │       ├── apple-icon-120x120.png
    │   │   │       ├── apple-icon-144x144.png
    │   │   │       ├── apple-icon-152x152.png
    │   │   │       ├── apple-icon-180x180.png
    │   │   │       ├── apple-icon-57x57.png
    │   │   │       ├── apple-icon-60x60.png
    │   │   │       ├── apple-icon-72x72.png
    │   │   │       ├── apple-icon-76x76.png
    │   │   │       ├── apple-icon.png
    │   │   │       ├── apple-icon-precomposed.png
    │   │   │       ├── browserconfig.xml
    │   │   │       ├── favicon-16x16.png
    │   │   │       ├── favicon-32x32.png
    │   │   │       ├── favicon-96x96.png
    │   │   │       ├── favicon.ico
    │   │   │       ├── manifest.json
    │   │   │       ├── ms-icon-144x144.png
    │   │   │       ├── ms-icon-150x150.png
    │   │   │       ├── ms-icon-310x310.png
    │   │   │       └── ms-icon-70x70.png
    │   │   └── v2
    │   │       ├── dc-g
    │   │       │   ├── dc-g.jpg
    │   │       │   └── dc-g.png
    │   │       ├── dc-g-preview.jpg
    │   │       └── favicon.ico
    │   │           ├── android-icon-144x144.png
    │   │           ├── android-icon-192x192.png
    │   │           ├── android-icon-36x36.png
    │   │           ├── android-icon-48x48.png
    │   │           ├── android-icon-72x72.png
    │   │           ├── android-icon-96x96.png
    │   │           ├── apple-icon-114x114.png
    │   │           ├── apple-icon-120x120.png
    │   │           ├── apple-icon-144x144.png
    │   │           ├── apple-icon-152x152.png
    │   │           ├── apple-icon-180x180.png
    │   │           ├── apple-icon-57x57.png
    │   │           ├── apple-icon-60x60.png
    │   │           ├── apple-icon-72x72.png
    │   │           ├── apple-icon-76x76.png
    │   │           ├── apple-icon.png
    │   │           ├── apple-icon-precomposed.png
    │   │           ├── browserconfig.xml
    │   │           ├── favicon-16x16.png
    │   │           ├── favicon-32x32.png
    │   │           ├── favicon-96x96.png
    │   │           ├── favicon.ico
    │   │           ├── manifest.json
    │   │           ├── ms-icon-144x144.png
    │   │           ├── ms-icon-150x150.png
    │   │           ├── ms-icon-310x310.png
    │   │           └── ms-icon-70x70.png
    │   ├── jpg
    │   │   ├── w1700
    │   │   │   ├── 4167x1668.jpg
    │   │   │   ├── 5000x1667.jpg
    │   │   │   └── 5001x1667.jpg
    │   │   └── w2500
    │   │       └── 2917x2500.jpg
    │   ├── png
    │   │   ├── w1700
    │   │   │   ├── 4167x1668.png
    │   │   │   ├── 5000x1667.png
    │   │   │   └── 5001x1667.png
    │   │   ├── w2500
    │   │   │   └── 2917x2500.png
    │   │   └── w600
    │   │       └── 600x600.png
    │   └── svg
    │       └── logo.svg
    └── sso
        └── ninja
            ├── 1200x1200.png
            ├── 40x40.png
            ├── 60x60.png
            └── 96x96.png
```
