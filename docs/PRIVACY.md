# Privacy

- Notes are stored only on your device and, if you choose, in the vault folder you pick. No notes, drawings or files are sent to the author or to third parties.
- No account, login, ads, tracking or usage analytics.
- The only network access is the update check: the app queries the project's GitHub releases (`api.github.com`) and, if you choose to update, downloads the installer from there. GitHub receives the usual technical data of any request (such as your IP address), covered by GitHub's own privacy policy.
- Device sync (optional): only after you pair with a code, the app exchanges notes and the Pro key, encrypted with AES-256-GCM, with your devices on the same local network. Nothing goes through the internet or to any server. A device name is announced on the network only after a device is paired or while a code is showing.
- Study AI (Pro, optional): only when you choose "Download the AI", the app downloads the model file from Hugging Face (`huggingface.co`): Qwen3 4B (~2.5 GB), on Android optionally Gemma 4 E2B (~2.6 GB), or on Windows optionally Qwen3 1.7B (~1.1 GB). Inference runs locally on the device; note text is never sent anywhere.
- Android permissions: access to the vault folder you select through the system folder picker, internet (updates only), Wi-Fi state and multicast (device sync on the local network), vibration (long-press feedback) and installing app updates (requested by Android when updating).
- Read aloud uses the device's own text-to-speech voice (Windows or Android). Station Notes doesn't send the text anywhere.
- If you activate Station Notes Pro, the key is stored on the device and in the vault folder. It contains the email used for the purchase and is verified offline.
- Automatic backups stay on the device: `Documents/Station Notes/backups` on Windows and `Android/data/app.notesdim/files/backups` on Android.
- To remove all data, uninstall the app and delete the vault folder and the backups folder.

See [LICENSE](../LICENSE) for the terms of use.

[Back to README](../README.md)
