GTA VI countdown site
=====================

1. Put your music file in this folder, next to index.html, and name it exactly:  song.mp3
2. Open index.html in Chrome, Edge, Firefox or Safari (double-click works).
3. The page loops the song forever. It tries to autoplay; browsers usually block sound
   until you click, so an "Enter with sound" button appears on the loading screen.
   After that the music fades in. The "Sound" button (bottom right) mutes and unmutes it.

Folder layout
  gta6-site/
    index.html
    song.mp3      <- you add this
    README.txt

Notes
- To use a different file name, change src="song.mp3" on the <audio> tag in index.html.
- GSAP and the fonts load from the internet, so you need to be online.
- If you publish the site publicly, make sure you have the rights to the music you add.
