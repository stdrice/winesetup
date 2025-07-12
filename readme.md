# winesetup
A simple shell script to automatically install and configure Wine for daily usage on most Linux distros.

# What does this script do?
- Install `wine-staging` and `winetricks`
- Setup `WINEPREFIX` and install components through `winetricks`
- Works on: Arch, Debian/Ubuntu, Fedora, openSUSE, Gentoo, Void
- (Soon) Install `Vulkan`
- (Soon) Install `wine-staging` manually on unsupported distros

# Usage
```
$ curl -L https://stdrice.github.io/winesetup/winesetup | bash
```

## Notes
- `bash` is required. Either `sudo` or `doas` installed.
