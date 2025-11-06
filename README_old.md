# MyWebsiteGIT
A GitHub Pages site hosting USDZ 3D models with thumbnails.

## Usage
1. Add `.usdz` files to the repository.
2. Run `./refresh.sh` to generate thumbnails, update `index.html`, and deploy to GitHub Pages.
3. Check `usdz_thumbnailer.log` for errors.

## Scripts
- **refresh.sh**: Swift script that generates PNG thumbnails for USDZ files, runs `generate_index_with_USDZ.sh`, and `deploy.sh`.
- **generate_index_with_USDZ.sh**: Creates `index.html` with USDZ links and thumbnails.
- **deploy.sh**: Commits and pushes changes to GitHub.

## Notes
- Requires macOS with Xcode/Swift installed.
- Older scripts (`usdz_thumbnailer.swift`, `usdz_thumbnailer`, `generate_usdz_thumbnails.sh`) are obsolete and have been removed.
