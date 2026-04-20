# T420s OpenCore Mountain Lion EFI

This repository provides a working **OpenCore EFI configuration** for running **macOS 10.8.5 (Mountain Lion)** on the **Lenovo ThinkPad T420s**.

___

## ⚠️ Important Notes

- Use **UEFI Only** boot mode (Legacy/CSM is not supported).
- If your model includes a optional NVIDIA GPU, it must be **disabled** (use integrated graphics only).
- For unknown reasons, using a 1600x900 resolution may cause lag. If you experience this issue, please lower the resolution.
- 
---

## ⚠️ Limitations

- **Wi-Fi and Bluetooth** are not functional due to the lack of compatible drivers for this macOS version and hardware.

---

## ✅ Working Features
- Graphics acceleration (Intel HD 3000)
- Keyboard and trackpad
- Audio (via VoodooHDA)
- Built-in webcam
- Ethernet (IntelMausiEthernet, a version I compiled myself for OS X 10.8)
- USB (except the rear port)

---

## ❓ Not Tested
- VGA output
- DisplayPort output
- DVD-ROM drive

---

## 📝 Notes

- A **blank white screen** may occasionally appear during boot after the system finishes loading.
    - This is a known issue.
    - **Temporary workaround:** simply reboot the system.
    - A permanent fix has not yet been identified.

---

## 📌 Additional Information
- This configuration is tailored specifically for the **ThinkPad T420s** and may require adjustments for other hardware variants.
- Only tested on **macOS 10.8.5**; compatibility with newer versions is not tested.

---

## Disclaimer

This project is intended for educational and experimental purposes only. Use at your own risk.