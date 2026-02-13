# Contributing to Nugget‑Wallpapers
Thank you for wanting to contribute to **Nugget‑Wallpapers**!

## How to Contribute
### 1. Submitting new your custom wallpaper(s)
If you want to add your own wallpaper:
1. Fork this repository and clone using the **`Dev`** branch.
2. Place your wallpaper `.tendies` file(s) in the `wallpapers/custom` folder.
<br>If you're uploading a `.batter` (template) file, place your wallpaper file in the `wallpapers/template` folder.
3. Add a preview video (`.mov` or `.mp4`) in `previews/custom`.
<br>Try to keep your previews as small as possible!
4. Make file names clear.
<br>E.g., `MarioGalaxy.tendies` and `MarioGalaxy.mp4`
5. Add metadata in [wallpapers-custom.json](#wallpapers-custom.json), you can fill in the template below.
<br>Place the data you filled right **below** `Animal Crossing Seasons` wallpaper.
<br>**Template** wallpapers can be put at the top in [wallpapers-template.json](#wallpapers-template.json)
```json
{
    "id": 1234567890,
    "name": "Your Wallpaper Name Here",
    "description": "Your Wallpaper Description Here",
    "url": "wallpapers/custom/YourWallpaperFileHere.tendies",
    "preview": "previews/custom/gifs/YourWallpaperPreviewHere.gif", // Keep this as .gif!
    "authors": "You", // Can be a social media @ or just your name.
},
```
If you're submitting multiple wallpapers or variations, bundle them in a single pull request with clear names and descriptions to keep it organized.

### 2. Submitting Apple™ Wallpaper(s)
At the moment we don't accept other wallpapers by Apple but if you you would like to have a Apple wallpaper, you can request it in the [PosterRestore Discord Server][posterestore_discord].

### 3. Reporting issues/suggesting ideas
If you encounter an issue or have an improvement idea:
1. Open an issue.
2. Provide a clear title and description.
3. Specify **which file or wallpaper** is affected and **what the problem or suggestion is**.
4. If you have a possible fix, amazing! Mention that you want to work on it or submit a PR directly.

---

## What we do NOT accept
- Copyrighted wallpapers without permission.
<br>Make sure you have the right to share.
- Explicit, offensive, or shocking content.
- Low-quality, blurry, or corrupted images.
- Disorganized PRs: do not combine too many unrelated changes in a single PR.

---

## Additional Information
- See the [README.md](#README.md) for project description, license, and usage.
- If you have questions, open an issue or join the [Cowabunga Discord Server][cowabunga_discord].

Thank you for contributing and helping build this wallpaper collection!

[cowabunga_discord]: https://discord.gg/cowabunga
[posterestore_discord]: https://discord.gg/gWtzTVhMvh
