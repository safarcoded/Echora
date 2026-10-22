ECHORA — seamless cinematic lyrics build

Files:
- homepage.html: music app. Cinematic Lyrics opens a full-screen overlay without navigating away.
- lyrics.html: cinematic 3D lyrics view. When embedded by the homepage, its player controls are bridged to the single audio player in homepage.html.
- assets/audio/Earrings.mp3: audio for the Earrings track. Keep this path unchanged unless you update the track src in homepage.html.
- lyrics-editor.html and timestamp JSON files: helper files for lyric timestamp edits.

Run locally through a static web server (recommended) or upload all files while preserving the directory structure. Keep homepage.html, lyrics.html, and assets/audio/Earrings.mp3 together in the same hosting root.

The first track, Earrings by Malcolm Todd, is wired to the supplied audio and synced lyric timeline. Other library entries remain demo placeholders, and the cinematic lyrics button is currently enabled for Earrings only until other tracks have matching audio and timestamped lyrics.
