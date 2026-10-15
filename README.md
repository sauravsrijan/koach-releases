# Koach releases

Built releases of **Koach**, a communication coach for macOS (Apple Silicon and Intel, macOS 13+). The source lives in a separate private repository; this repo only hosts release builds. Installed copies of Koach update themselves from here.

## Install

1. Download `Koach-<version>-universal.zip` from the [latest release](https://github.com/sauravsrijan/koach-releases/releases/latest) and unzip it.
2. Move `Koach.app` to **Applications**.
3. Koach isn't notarized yet, so clear the download quarantine once:

   ```sh
   xattr -dr com.apple.quarantine /Applications/Koach.app
   ```

4. Open Koach and follow the setup.

After that, Koach checks for updates on its own and offers to restart when one is ready.
