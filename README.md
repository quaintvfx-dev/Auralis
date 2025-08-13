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

## 🎵 About Auralis

Auralis is a fully AI-developed music player designed specifically for lossless audio codecs.

- Works with lossy formats, but optimal quality is achieved with lossless audio when paired with **LAVFilters**.  
- This is an **early build**; some bugs or performance issues may be present.  
- Feedback is welcome to help refine the experience.

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
