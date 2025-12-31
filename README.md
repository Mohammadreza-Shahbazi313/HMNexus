# HMNexus 🧬💻  
> A **graphical, code-free**, and **high-speed** desktop application for downloading TCGA data from the Genomic Data Commons (GDC).

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-green)](https://www.python.org/)
[![PyQt5](https://img.shields.io/badge/GUI-PyQt5-orange)](https://www.riverbankcomputing.com/software/pyqt/)
![GitHub Release](https://img.shields.io/github/v/release/Siamak-salimy/HMNexus)

HMNexus empowers biologists, clinicians, and researchers **without programming expertise** to access The Cancer Genome Atlas (TCGA) data through an intuitive point-and-click interface. Built with **Python + PyQt5**, it supports **manifest-based parallel downloads** directly from the GDC portal—up to **4.8× faster** than standard tools—while automatically organizing files for downstream analysis.

> 📌 **Note**: HMNexus is the official name of the tool formerly referred to as "TCGADownloader" in early development.

---

## ✨ Key Features

- ✅ **Zero coding required** – fully graphical interface  
- ⚡ **High-speed concurrent downloads** via GDC manifest files  
- 🧩 **Interactive filtering** by cancer type, data category (e.g., RNA-seq, clinical, methylation), and sample attributes  
- 📁 **Automatic file organization** (e.g., `BRCA/clinical/`, `LUAD/rnaseq/`)  
- 🔒 **MD5 checksum validation** for data integrity  
- 🌐 **Cross-platform**: Windows, macOS, Linux  
- 📦 **Standalone executables** available (no Python needed)  
- 🆓 **Open-source** under MIT License

---

## 🚀 Quick Start

### Option 1: Download Executable (Recommended)
1. Go to [Releases](https://github.com/Siamak-salimy/HMNexus/releases)
2. Download the file for your OS:
   - 🪟 **Windows**: `HMNexus-*-Windows.exe`
   - 🍏 **macOS**: `HMNexus-*-mac.dmg`
   - 🐧 **Linux**: `HMNexus-*-Linux.tar.gz`
3. Run it — no installation or Python required!

### Option 2: Run from Source
```bash
git clone https://github.com/Siamak-salimy/HMNexus.git
cd HMNexus
pip install -r requirements.txt
python main.py
