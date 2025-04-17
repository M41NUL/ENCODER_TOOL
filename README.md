![ENCODER_TOOL](https://github.com/M41NUL/ENCODER_TOOL/blob/main/Screenshot_2025-04-17-12-06-56-162_com.termux.jpg)
<p align="center"><b>A Powerful Python Encoder Tool By MAINUL ISLAM</b></p>

---

# ENCODER_TOOL

**Developer**: MAINUL ISLAM

A Python-based terminal tool to encode your Python scripts using various encoding methods like Marshal + Base64, py_compile, Base64 only, HEX encoding, and Obfuscation.

---

## Features

- Encode scripts using:
  - Marshal + Base64
  - py_compile (.enc.py)
  - Base64 only
  - HEX encoding
  - Obfuscation (basic shift cipher)
- File backup option
- Easy terminal interface
- Works on **Termux** and **Pydroid3**

---

## Installation (Termux Users)

Run the following commands one by one in Termux:

### Remove old version:
```bash
cd ~
rm -rf ENCODER_TOOL
```

### Install tool:
```bash
apt update -y
apt upgrade -y
pkg install python -y
pkg install git -y
pip install pyfiglet
git clone https://github.com/M41NUL/ENCODER_TOOL
cd ENCODER_TOOL
python3 encoding_tool.py
```

---

## Usage

After running the tool, you’ll see a menu like:

```
1. Marshal + Base64  
2. py_compile (.enc.py)  
3. Base64 Only  
4. HEX Encode  
5. Obfuscate (Basic Shift Cipher)  
6. Create Backup of File  
0. Exit
```

- Enter your choice number (e.g., `1` for Marshal + Base64)
- Then enter the full path to your Python file (e.g., `/sdcard/Download/test.py`)
- Then enter the output filename (without `.py` extension)
- Done! Encoded file will be created in your current directory.

---

## Screenshot

![Screenshot](https://github.com/M41NUL/ENCODER_TOOL/blob/main/Screenshot_2025-04-17-12-06-56-162_com.termux.jpg)
![Screenshot](https://github.com/M41NUL/ENCODER_TOOL/blob/main/Screenshot_2025-04-17-12-07-59-378_com.termux.jpg)

---

## Contact

- **Developer**: Mainul Islam  
- **GitHub**: [M41NUL](https://github.com/M41NUL)  
- **Telegram**: [@MAINUL_X](https://t.me/mdmainulislaminfo)  
- **WhatsApp**: [+8801308850528](https://wa.me/8801308850528)  
- **Email**: [nextleveldigitalbd@gmail.com](mailto:nextleveldigitalbd@gmail.com)

---

## Warning

> This tool is for **educational purposes only**. The developer is **not responsible** for any kind of misuse. Use at your own risk.
