# 🎛️ Codecs

- A codec is a software or hardware component that **compresses** and **decompresses** digital media files.
- It allows for **efficient storage**, **transmission**, and **playback** of audio and video content.

> 📚 For video codecs, see the Digital Video Processing workshop:
> <https://github.com/mr-pylin/video-processing-workshop>

## 🖼️ **Image Codecs**

### **BPG (Better Portable Graphics)**

A high-efficiency image format designed to provide better compression and quality than JPEG by using the HEVC (High Efficiency Video Coding) standard

- 📥 Download
  - Executable (.exe) files are officially available at the [official site](https://bellard.org/bpg/).
  - Link: [bellard.org/bpg/bpg-0.9.8-win64.zip](https://bellard.org/bpg/bpg-0.9.8-win64.zip)
- 🛠️ Usage
  - To Encode:

    ```bash
    ./bpgenc.exe <input.[jpg|png]> -o <encoded.bpg> -m 9
    ```

  - To Decode:

    ```bash
    ./bpgdec.exe -o <decoded.[ppm|png]> <encoded.bpg>
    ```

- ©️ Source Code
  - Encoder & Decoder: [bellard.org/bpg/libbpg-0.9.8.tar.gz](https://bellard.org/bpg/libbpg-0.9.8.tar.gz).
