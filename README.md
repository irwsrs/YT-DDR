Helper scripts to convert songs from YouTube to full-length playable Stepmania tracks via Autostepper by phr00t

Requires: youtube-dl, ffmpeg, Autostepper by phr00t 

1. Unzip into your Autostepper/dist folder

2. Execute youtube-dl.sh  
Paste YT link--video or playlist OK  
If playlist, check /input to make sure all songs were downloaded

3. Execute make-step.sh  
If playlist, check /output to make sure all songs were converted

Your new Stepmania songs are now in your /output folder 🤩

Generally if the outputs are ~90-120 BPM for normal tempo, or 120-160 for fast tempo, the song is playable. About half to two-thirds of songs come out well. You can also set BPM manually with Autostepper. But if you're doing that, you probably don't need these helper scripts.

Tested with hundreds of tracks of varying genres.  
YMMV
