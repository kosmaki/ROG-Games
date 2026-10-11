ROG site
========
index.html   the whole website (edit the `games` list near the bottom to add games)
sounds/      the SteamOS sound effects (keep the file names)
images/      put game cover images here, then set `image: "images/xyz.jpg"` for that game
games/       put each game in its own folder, then set `url: "games/xyz/index.html"`

Publish: unzip, then upload the CONTENTS of this folder to your GitHub repo
(Settings > Pages > deploy from main branch, root).
Open locally by double-clicking index.html (sounds work too).
