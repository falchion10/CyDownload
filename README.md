Built with Qt 6.9.3

Focused on building for Apple Silicon Macs running macOS 11.0 and later.

# Building and running

## macOS
`git clone https://github.com/falchion10/CyDownload.git`

`cd cydownload`

`qmake cydownload.pro`
May need to add `CONFIG+=sdk_no_version_check` to qmake on macOS Tahoe for now.

~~You might need to remove `-framework AGL` from the Makefile, I have no idea why it's being added or how. AGL was deprecated in macOS 10.11~~

No longer needed to remove AGL framework from the Makefile as in macOS Tahoe the framework has been completely removed.

`make`

run `CyDownload.app` and it will open successfully.
