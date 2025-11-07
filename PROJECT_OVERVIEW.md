# 🧬 VDCL – Virtual DNA Coding Language

**Inventor:** Chandan Parihar Mali (C. P. Mali)  
**Repository:** [VDCL-Virtual-DNA-Coding-Language](https://github.com/cpmali5132-crypto/VDCL-Virtual-DNA-Coding-Language)

---

### 🔹 Overview
VDCL (Virtual DNA Coding Language) is a novel **text-to-DNA encoding system** designed for next-generation molecular data storage.

**Key Features**
- Text ↔ DNA Encoder/Decoder (triplet-based codon map)
- `.vdl` / `.vdp` file format with CRC32 integrity
- AES-256 encryption/decryption (Fernet layer)
- 3D double-helix visualizer using Plotly
- Auto-generated encoding animation (MP4)

---

### 🧩 Run Instructions
```bash
pip install streamlit plotly imageio imageio-ffmpeg cryptography matplotlib
streamlit run vdcl_studio_v4_single.py
