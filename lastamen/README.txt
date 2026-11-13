THE LAST AMEN — V5, USER TMX REBUILD

Open index.html in a browser. For GitHub Pages, upload the whole folder contents.

The main floor renders EXACTLY from LastAmenScratchMap.tmx, supplied by you.
The ground-floor collision is generated from the TMX Carpet and Walls layers:
 floor tile = walkable; any wall tile = solid; unpainted floor = impassable.
The upstairs landing is the separate map from the previous version.
Your Tiled file is included in maps/LastAmenScratchMap_with_collision.tmx with local tileset paths.

Controls: WASD / arrow keys to move, E or Space to interact, M map, J journal.
Five scripture challenges, ghosts, eight folding chairs and two endings are retained.

TMX markers inferred from the icon art: Scripture note in gym=Genesis 19; Primary note=Babel; east hallway=3 Nephi 11; west side=1 Nephi 8; upstairs table=Matthew 26.
The player's start is the east vestibule.

IMPORTANT: map-data.js was exported from the TMX at build time. To apply future edits to the TMX, regenerate map-data.js; editing the TMX by itself will not live-update the browser game.
The other files in assets/ are required. Keep them together on GitHub Pages.
