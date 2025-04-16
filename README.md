# Video Encryptor – Proof-of-Concept Project

**Video Encryptor** is a prototype developed to demonstrate the encryption of video files for secure streaming or offline protection. This was built as an early project to understand file-level security and cryptographic integration with multimedia pipelines.

---

## 💡 Use Case

- DRM-like content protection for local playback
- Obfuscation of raw video files on disk
- Playback only via decryption key/method

---

## 🛠️ Tech Stack

- Java (if used)
- XML configuration (for control or metadata)
- FFmpeg or native video handling libraries (if applicable)
- Basic GUI (Swing/JavaFX) or CLI tool
- Custom encryption algorithm or AES/Blowfish

---

## 📦 Installation

> _Adjust if compiled via Eclipse/IntelliJ_

```bash
git clone https://github.com/skywalker-/video_encrypt.git
cd video_encrypt
javac *.java
java Main
