# Play Acoustic Library

Community preset library for the TC Helicon Play Acoustic and Play Electric.

Presets are browsed, imported, and submitted entirely through the **[Play Acoustic Editor](https://oddeyez.github.io/PlayAcousticEditor)** — not by editing files in this repo directly.

## Downloading presets

Open the editor and click **Library** in the toolbar. From there you can search, browse, and import presets directly into your device.

You can also clone or download this repo to get the raw `.tch` files.

## Sharing a preset

1. Open the [Play Acoustic Editor](https://oddeyez.github.io/PlayAcousticEditor)
2. Load your preset file
3. Click **Share** on the preset you want to submit
4. Fill in the details and click **Open GitHub Issue →**

That's it — the editor handles everything. Do not open issues or pull requests manually.

## Structure

```
acoustic.json       # Metadata index for Play Acoustic presets
electric.json       # Metadata index for Play Electric presets
presets/            # .tch binary preset files
```

### Metadata entry format

```json
{
  "name": "PRESET NAME",
  "author": "Your Name",
  "authorHash": "sha256-of-your-author-code",
  "shortDesc": "One-liner shown in the library list",
  "desc": "Full description with tips and use cases",
  "categories": ["Harmony", "Pop"],
  "keywords": ["warm", "tight", "fingerpicking"],
  "file": "presets/your-preset.tch"
}
```
