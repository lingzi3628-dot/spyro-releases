# Spyro Releases

Download official Spyro desktop builds from the [latest release](https://github.com/lingzi3628-dot/spyro-releases/releases/latest).

## Downloads

- **Windows:** `.exe` installer
- **macOS:** `.dmg` disk image
- **Linux:** `.AppImage` or `.deb` package
- **Portable:** `.tar.gz` archive when included in the release

Open a release and choose the file for your operating system. Linux AppImages may need execute permission first:

```sh
chmod +x Spyro*.AppImage
./Spyro*.AppImage
```

Each release includes `SHA256SUMS` so you can verify downloaded files. From a terminal in the download folder, run:

```sh
sha256sum -c SHA256SUMS
```

## Project

Spyro source code is maintained in the [private source repository](https://github.com/lingzi3628-dot/claude-spyro). Report release download issues in this repository's [Issues](https://github.com/lingzi3628-dot/spyro-releases/issues).
