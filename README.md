# Beyond the Frame — Music Film

An original, browser-based audiovisual film for **Beyond the Frame**.

## Run

Open [the music film](https://trandonweb.github.io/mv_Trandon/) after GitHub Pages finishes deploying, or serve this repository locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

The film uses the original track at `songs/Beyond the Frame.mp3`. Press **Play** to start; the visuals respond to the music. Use the progress line to seek, **SOUND ON/OFF** to mute, and double-click the image to toggle fullscreen.

## Production notes

- 4:22 runtime
- Canvas-based generative visuals, synchronized to playback time and live audio energy
- Responsive layout for desktop and mobile
- No external libraries or remote assets
