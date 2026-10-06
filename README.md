# Tinker releases

Prebuilt Tinker builds for macOS (Apple Silicon). This repository holds release downloads only.

Installed copies of Tinker check for updates themselves and offer **Restart to update**.

## Install by hand

1. Download `Tinker-arm64.zip` from the [latest release](https://github.com/nullcolor-app/tinker-releases/releases).
2. Unzip it and move `Tinker.app` to Applications.
3. These builds aren't notarized yet, so macOS reports a downloaded copy as damaged. Clear the download flag once before opening it:

   ```
   xattr -dr com.apple.quarantine /Applications/Tinker.app
   ```

4. Open Tinker.

The same files are published at `https://tinker-releases.nullcolor.app/`
(`latest.json` names the newest release).

Every build carries its license in `Tinker.app/Contents/Resources/LICENSE`.
