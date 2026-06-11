# Play Acoustic Library

Community preset library for the [TC Helicon Play Acoustic](https://www.tc-helicon.com/product.html?modelCode=P0DTD) and Play Electric, managed through the [Play Acoustic Editor](https://github.com/oddeyez/PlayAcousticEditor).

## Structure

```
acoustic.json       # Metadata index for Play Acoustic presets
electric.json       # Metadata index for Play Electric presets
presets/            # .tch preset files
```

### Index entry format

```json
{
  "name": "PRESET NAME",
  "author": "Your Name",
  "authorHash": "sha256-of-your-author-code",
  "shortDesc": "One-liner shown in the library list (max 100 chars)",
  "desc": "Full description — tips, use cases, what to expect",
  "categories": ["Harmony", "Pop"],
  "keywords": ["warm", "tight", "fingerpicking"],
  "file": "presets/your-preset.tch"
}
```

## Contributing a preset

1. Open the preset in the Play Acoustic Editor
2. Click **Share** on the preset you want to submit
3. Fill in author, descriptions, categories, and keywords
4. Click **Open GitHub Issue →** — a pre-filled issue will open here
5. Submit the issue

The maintainer will review, decode the preset data, commit the `.tch` file, and add the metadata entry to the appropriate index.

## Editing or removing your preset

Open the library browser in the editor, find your preset, and click **Your preset ▾** (or **Verify ownership** on a new device). From there you can update metadata, replace the preset data, or request removal.

## Labels

| Label | Meaning |
|---|---|
| `community-preset-acoustic` | New preset submission for Play Acoustic |
| `community-preset-electric` | New preset submission for Play Electric |
| `community-edit` | Update metadata or replace preset data |
| `community-remove` | Remove a preset |
