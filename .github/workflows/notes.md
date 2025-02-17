```
${NVIM_VERSION}
```

## Install

### Windows

#### Zip

1. Download **nvim-win64.zip**
2. Extract the zip.
3. Run `nvim-qt.exe`

#### MSI

1. Download **nvim-win64.msi**
2. Run the MSI
3. Add the Neovim location to your path.
   - Default location is `C:\Program Files\Neovim`
4. Search and run `nvim-qt.exe` or run `nvim.exe` on your CLI of choice.

#### NSIS

1. Download **nvim-win64.exe**
2. Run the installer.
   - Ensure that the option to add the installation location to your path is checked if it's your first installation.
3. Search and run `nvim-qt.exe` or run `nvim.exe` on your CLI of choice.

### macOS

1. Download **nvim-macos.tar.gz**
2. Extract: `tar xzvf nvim-macos.tar.gz`
3. Run `./nvim-osx64/bin/nvim`

### Linux (x64)

#### Tarball

1. Download **nvim-linux64.tar.gz**
2. Extract: `tar xzvf nvim-linux64.tar.gz`
3. Run `./nvim-linux64/bin/nvim`

#### Debian Package

1. Download **nvim-linux64.deb**
2. Install the package using `sudo apt install ./nvim-linux64.deb`
3. Run `nvim`

#### AppImage
1. Download **nvim.appimage**
2. Run `chmod u+x nvim.appimage && ./nvim.appimage`
   - If your system does not have FUSE you can [extract the appimage](https://github.com/AppImage/AppImageKit/wiki/FUSE#type-2-appimage):
     ```
     ./nvim.appimage --appimage-extract
     ./squashfs-root/usr/bin/nvim
     ```

### Other

- Install by [package manager](https://github.com/neovim/neovim/wiki/Installing-Neovim)

## SHA256 Checksums

```
${SHA_LINUX_64_TAR}
${SHA_LINUX_64_DEB}
${SHA_APP_IMAGE}
${SHA_APP_IMAGE_ZSYNC}
${SHA_MACOS}
${SHA_WIN_64_ZIP}
${SHA_WIN_64_MSI}
${SHA_WIN_64_EXE}
```
