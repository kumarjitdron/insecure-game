# Insecure Reverse Engineering Practice App

## 📘 Description
This project is an **intentionally vulnerable Android application** created **for educational purposes only**, to help learners practice **reverse engineering and application security testing**.  
It contains multiple challenges that simulate real-world vulnerabilities — allowing safe experimentation in a controlled environment.

> ⚠️ **Disclaimer:**  
> This app is designed **only for learning and research**.

---

## 🧩 Features & Challenges

The app includes several intentionally insecure modules for practice:

1. **Root Check Bypass** – Detects rooted devices; can be bypassed through patching or hook.  
2. **PIN Verification Bypass** – PIN-based login logic vulnerable to static patching.  
3. **Admin Access via JWT Forging** – Weak JWT implementation allows privilege escalation.  
4. **Ads Banner Removal** – Simple ads integration that can be disabled or bypassed.  
5. **Rock–Paper–Scissors Logic Bypass** – Game logic can be reversed or modified to always win.  
6. **Snake Game Logic Bypass** – Classic snake game that can be manipulated to achieve impossible scores.  
7. **Command Injection (Reverse Engineering Challenge)** – Hidden command executor vulnerable to injection.  
8. **Hidden Payment Gateway Feature** – A demonstration-only feature (not part of reverse engineering challenges).

---

## ⚙️ Usage
- Install the APK on a **test device or emulator** (do not use on personal devices).  
- Analyze and modify the app using **reverse engineering tools** like:
  - `jadx-gui`
  - `apktool`
  - `smali code modification`
  - `Ghidra`
- Each challenge can be tackled independently.

---

## 📄 License
This project is released under the **MIT License** for educational use.

---

## 👨‍💻 Author
**Kumarjit Dron**  
GitHub: [@kumarjitdron](https://github.com/kumarjitdron)
