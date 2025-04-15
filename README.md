# PyObfuscator.com Deobfuscator

A Python tool to analyze and reverse obfuscation produced by [pyobfuscator.com](https://pyobfuscator.com/). This project is intended for **educational** and **security research** purposes only.

## 🔍 Overview

This tool helps reverse Python code obfuscated using the online service `pyobfuscator.com`. Its goal is to aid in:

- Security auditing
- Malware analysis
- Educational exploration of obfuscation techniques
- Reverse engineering training

⚠️ **This is *not* a hacking tool.** It is designed strictly for use in legitimate scenarios such as code recovery, malware sandboxing, or learning how obfuscation techniques work.

---

## 🚀 Features

- Detects common patterns used by `pyobfuscator.com`
- Reconstructs human-readable source code
- Supports dynamic execution and decoding
- Optional zlib decompression and hex dumping
- Lightweight and easy to extend

---

## ⚠️ Legal & Ethical Use Disclaimer

> This tool is provided for **educational and ethical purposes only**.  
> The author(s) are **not responsible** for any misuse or damage caused by this tool.

You are **only allowed** to use this tool:
- On code you own or have permission to analyze.
- For the purpose of ethical research, malware analysis, or educational demonstrations.

❌ Do **not** use this tool to:
- Deobfuscate commercial/proprietary code you do not have rights to.
- Assist in software piracy, license bypassing, or any form of illegal distribution.
- Spread, analyze, or modify malicious code unless you are in a controlled and lawful security research environment.

By using this tool, you agree to comply with your local laws and regulations.

---

## 🛠️ Installation

```bash
git clone https://github.com/Seeking-jpg/pyobfuscator-deobfuscator
cd pyobfuscator-deobfuscator
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
