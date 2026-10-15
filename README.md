# Koach releases

Built releases of **Koach**, a communication coach for macOS (Apple Silicon and Intel, macOS 13+). The source lives in a separate private repository; this repo only hosts release builds. Installed copies of Koach update themselves from here.

## Install

1. Download `Koach-<version>-universal.dmg` from the [latest release](https://github.com/sauravsrijan/koach-releases/releases/latest), open it, and drag **Koach** onto **Applications**.
2. Koach isn't notarized yet, so macOS blocks the first launch. Either run this once in Terminal:

   ```sh
   xattr -dr com.apple.quarantine /Applications/Koach.app
   ```

   or open Koach, then go to **System Settings → Privacy & Security** and click **Open Anyway**.
3. Follow the setup (your name, Microphone and Screen Recording, your API keys).

After that, Koach checks for updates on its own and offers to restart when one is ready.
