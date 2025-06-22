Built with Qt 6.9.0

Focused on building for Apple Silicon Macs running macOS 11.0 and later.

# Building and running

## macOS
`git clone https://github.com/falchion10/CyDownload.git`

`cd cydownload`

`qmake cydownload.pro`

You might need to remove `-framework AGL` from the Makefile, I have no idea why it's being added or how. AGL was removed in macOS 10.11

`make`

run `CyDownload.app` and it will open successfully.
