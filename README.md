# Reflection

A browser-based infinite mirror effect — your face, recursively looping into itself.

**[Try it →](https://shohei81.github.io/reflection/)**

## How it works

Each frame, the previous canvas is scaled down and composited back onto itself, creating a tunnel of recursively smaller images. The effect works with a webcam, a screen capture, or any video file.

## Controls

| Key | Action |
|-----|--------|
| `1` – `0` | Rotation per level (0° → 180°) |
| `+` / `-` | Frame scale (depth) |
| `A` | Toggle audio delay feedback |
| `←` `→` | Delay time |
| `↑` `↓` | Feedback amount |
| `W` | Webcam overlay (Screen / Video file mode) |
| `F` | Fullscreen |
| `R` | Record / stop & download |
| `Esc` | Exit |

## Sources

- **Camera** — webcam feed
- **Screen** — any tab or window (check "Share audio" for audio delay)
- **Video file** — local MP4 / WebM, loops automatically
