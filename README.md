# Batch Video-to-Podcast Audio Prep

A fast, offline Windows desktop utility for extracting, cleaning up, normalizing, and converting audio from video and audio files in bulk.

Built for podcasters, video creators, voiceover artists, and musicians who want reliable one-click audio preparation without cloud upload limits, subscriptions, or complex DAW setup.

---

## Key Features

* **Bulk Extraction & Conversion:** Drag and drop files or entire folders (including subfolders) to extract audio from video or convert between formats in a single batch pass.
* **Smart Format & Bitrate Presets:**
  * **MP3 (Match Source Bitrate):** Automatically detects each source file's bitrate and matches it without unnecessary file bloat.
  * **MP3 (320 kbps & 192 kbps):** High-bitrate constant encoding for music or spoken-word distribution.
  * **WAV & FLAC (Lossless):** Uncompressed 16-bit PCM WAV (44.1 kHz) and lossless FLAC exports.
* **EBU R128 Loudness Normalization:** One-click integrated loudness targets for **Podcast (-16 LUFS)**, **YouTube / Video (-14 LUFS)**, **Audiobook / Broadcast (-23 LUFS)**, or **No Normalization**.
* **Automated Audio Cleanup & Fades:**
  * **Silence Trimming:** Removes leading and trailing dead air below `-50 dB`.
  * **Spoken-Word Mono Downmix:** Combines stereo channels to mono to halve file sizes and prevent phase issues.
  * **Smooth Fades (0.0s – 10.0s):** Applies fade-in and fade-out ramps in `0.1s` increments *after* silence trimming so fades start and end cleanly on actual audio.
* **Safe Output Naming & Mid-Batch Cancellation:** Appends active processing settings to output filenames so original files are never overwritten, and lets you cancel a running batch immediately with automatic cleanup of incomplete files.
* **100% Local & Private:** Powered by a bundled FFmpeg engine—your files never leave your computer.

---

## Supported Input Formats

* **Video:** `.mp4`, `.mkv`, `.mov`, `.avi`, `.wmv`, `.flv`, `.webm`
* **Audio:** `.mp3`, `.wav`, `.flac`, `.m4a`, `.aac`, `.ogg`, `.wma`

---

## System Requirements

* **OS:** Windows 10 or Windows 11 (64-bit)
* **Dependencies:** None (standalone executable with FFmpeg and User Guide included)

---

## Download & Purchase

* **Get the Windows App:** [Download on Payhip](https://payhip.com) *(replace with your Payhip product URL)*

---

## Bug Reports & Feature Requests

Have an idea for a new preset or found an issue?

1. Open the [**Issues**](https://github.com) tab at the top of this repository.
2. Click **New issue** and include your Windows version, input file format, and selected processing settings.

---

## Third-Party Attribution

This software uses **FFmpeg** (licensed under the LGPLv2.1 / GPLv2+) for local audio extraction, filtering, and encoding.
