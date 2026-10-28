# Privacy

- Notes are stored only on your device and, if you choose, in the vault folder you pick (for example a Syncthing folder). No notes, drawings or files are sent to the author or to third parties.
- No account, login, ads, tracking or usage analytics.
- The only network access is the update check: the app queries the project's GitHub releases (`api.github.com`) and, if you choose to update, downloads the installer from there. GitHub receives the usual technical data of any request (such as your IP address), covered by GitHub's own privacy policy.
- Study AI (Pro, optional): only when you choose "Download the AI", the app downloads the model file in GGUF format from Hugging Face (`huggingface.co`): Qwen3 4B (~2.5 GB) or, on Windows, optionally Qwen3 1.7B (~1.1 GB). Inference runs locally on the device; note text is never sent anywhere.
- Android permissions: access to the vault folder you select through the system folder picker, internet (updates only), vibration (long-press feedback) and installing app updates (requested by Android when updating).
- Read aloud uses the device's own text-to-speech voice (Windows or Android). Notes Dim doesn't send the text anywhere.
- If you activate Notes Dim Pro, the key is stored on the device and in the vault folder. It contains the email used for the purchase and is verified offline.
- Automatic backups stay on the device: `Documents/Notes Dim/backups` on Windows and `Android/data/app.notesdim/files/backups` on Android.
- To remove all data, uninstall the app and delete the vault folder and the backups folder.

See [LICENSE](../LICENSE) for the terms of use.

[Back to README](../README.md)
