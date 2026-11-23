# Desktop Fishing artwork

Static inventory artwork for Desktop Fishing: 16 fish, their public item IDs/names and rarity colours, and a small preview page.

Site: https://hampusbrink.github.io/desktop-fishing-assets/

Example direct image URL: https://hampusbrink.github.io/desktop-fishing-assets/items/clown-fish.png

The original PNGs remain in `items/`. Centred 200×200 thumbnails are in `items/icons-v2/` and 2048×2048 large images in `items/large-v2/`, and 660×384 wide images for the Steam inventory detail view in `items/large-wide-v3/` (same art as `items/large-wide/`, new path so Steam fetches it again; every fish at one fixed 12× pixel scale) (use these as `icon_url_large` so the fish sits centred in Steam's wide image box). The visible artwork is fitted inside each transparent canvas with a margin on all sides. These are nearest-neighbour upscales of the 32×32 pixel-art fish icons used in the game, so every pixel stays crisp. No Unity project, source code, save files or credentials are published here.

To replace an image, upload a PNG using the same path, or use a new filename and update the item's `icon_url` and `icon_url_large` in Steamworks. A new filename is useful when Steam has cached an earlier image. Re-upload the item definitions after changing their URLs.

GitHub Pages publishes the root folder of the `codex/steam-inventory-images` branch. `.nojekyll` keeps the files as plain static assets. This is an artwork preview site; purchases and trading happen on Steam, not here.

Artwork remains the property of its respective rights holders; no reuse license is granted by this repository.
