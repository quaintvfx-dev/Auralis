# 🎧 Auralis – High-Fidelity Music Player

Created by:  
[sevunteen](https://discord.com) (Discord) / [quaintvfx](https://tiktok.com) (TikTok, Instagram)  
Developed in collaboration with Claude 4 Sonnet and ChatGPT 5  

---

## 🎵 About Auralis

Auralis is a fully AI-developed music player designed specifically for lossless audio codecs.

- Works with lossy formats, but optimal quality is achieved with lossless audio when paired with **LAVFilters**.  
- This is an **early build**; some bugs or performance issues may be present.  
- Feedback is welcome to help refine the experience.

---

## ⚠️ Disclaimer
Auralis may trigger a **false positive virus flag** in some antivirus software.  
This is a common occurrence with custom-built executables and does **not** indicate malicious behavior.  
You can verify the authenticity of your download using the SHA256 hash provided with each release.

## 🔒 Verification Instructions

Each release includes a `.sha256` file containing the SHA256 hash of the build.  
To verify your download:

- **Windows PowerShell**  
  ```powershell
  Get-FileHash .\Auralis.exe -Algorithm SHA256
  ```
- **Linux / macOS**  
  ```bash
  sha256sum Auralis.exe
  ```

Compare the result with the contents of `Auralis.exe.sha256`.  
If they match exactly, your file is authentic.

---

## 📥 Installation Instructions

1. **Install VLC**  
   - Use the installer provided in the extracted `.rar` archive.  
   - VLC is required for Auralis to function, and is also an excellent video player.

2. **(Optional) Install LAVFilters**  
   - Strongly recommended for full access to high-fidelity audio.  
   - Without LAVFilters, audio capabilities will be significantly limited.

3. **Launch Auralis and Enjoy 🎵**

---

## 🎶 Supported Audio Formats

**Lossless – Uncompressed PCM**  
`WAV, WAVE, W64, AIFF, AIF, CAF, AU, SND`

**Lossless – Compressed**  
`FLAC, ALAC, APE, WV, TTA`

**Lossless – DSD**  
`DSF, DFF`

**Lossy**  
`MP3, MP2, MP1, AAC, AC3, OPUS, SPX, WMA, MPC, AMR`

**Tracker & MIDI**  
`MOD, S3M, XM, IT, MID, MIDI`

**Containers / Wrappers – May hold various codecs**  
`OGG, OGA, M4A, M4B, MKA`

---

## 💡 Note
For the best possible listening experience, install **LAVFilters** and use **high-quality lossless audio sources**.
