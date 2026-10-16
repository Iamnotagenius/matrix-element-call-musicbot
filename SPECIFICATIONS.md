Runtime Specifications

- Python: 3.11+
- Node.js: 22.x
- Bun: installs the call worker dependencies (the worker itself runs on Node)
- ffmpeg: required in PATH
- yt-dlp: required in PATH (youtube-dlp also supported)

Python dependency installation

- `pip install -r requirements.txt`

Node worker dependency installation

- `bun install --cwd call_worker --frozen-lockfile`
