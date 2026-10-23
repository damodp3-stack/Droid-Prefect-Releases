# 🛡️ Droid Prefect — Official Releases & Downloads

<p align="center">
  <img src="assets/icon.png" alt="Droid Prefect Icon" width="160px" style="border-radius: 32px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
</p>

<h1 align="center">Droid Prefect</h1>

<p align="center">
  <strong>🔒 The Hardened, Autonomous, Zero Data-Theft AI Agent for Android</strong>
</p>

<p align="center">
  <a href="https://github.com/damodp3-stack/Droid-Prefect-Releases/releases/latest">
    <img src="https://img.shields.io/badge/Release-v1.0.9-brightgreen?style=for-the-badge&logo=android" alt="Release">
  </a>
  <img src="https://img.shields.io/badge/Platform-Android%208.0+-blue?style=for-the-badge&logo=google" alt="Platform">
  <img src="https://img.shields.io/badge/Security-SHA--256%20Verified-purple?style=for-the-badge&logo=shield" alt="Security">
</p>

---

## ⬇️ Download Droid Prefect

Get the latest production release of Droid Prefect directly to your Android device:

<p align="center">
  <a href="https://github.com/damodp3-stack/Droid-Prefect-Releases/releases/download/v1.0.9/DroidPrefect.apk">
    <img src="https://img.shields.io/badge/Download-DroidPrefect.apk%20(55.2%20MB)-0284C7?style=for-the-badge&logo=android&logoColor=white" alt="Download APK" height="48">
  </a>
</p>

| Package | Version | Build | Size | SHA-256 Integrity Hash |
| :--- | :--- | :--- | :--- | :--- |
| `DroidPrefect.apk` | **v1.0.9** | `10` | `55.2 MB` | `dfa87362bd20f7327b3606caadc352c86e02847a705e7aa916b9a4ca5f9740b1` |

*All previous builds are available on the [GitHub Releases Archive](https://github.com/damodp3-stack/Droid-Prefect-Releases/releases).*

---

## 🚀 What's New in v1.0.9

- **🛡️ Eliminated Security & Financial Loss Alerts:**
  - Removed high-risk direct telephony permissions (`CALL_PHONE`, `SEND_SMS`, `READ_SMS`, `RECEIVE_SMS`) that triggered OEM Phone Manager & Play Protect flags.
  - Calling and SMS actions now seamlessly and safely delegate via Android standard intents with Accessibility Service automation.
- **💬 Instant Greeting & Chat Fallback:**
  - Instant offline greetings for "hi", "hey", "hello", "vanakkam", "help" without needing any LLM loaded.
  - If no model is downloaded or API key is absent, the assistant displays a clear instruction card with a direct path to download offline models in Settings.
- **⚡ Default Offline Mode:**
  - On-Device AI is now the default provider out of the box with zero external token requirements.
- **🧠 Open-Source Model Hub:**
  - One-tap download for Qwen 2.5 0.5B, Qwen 2.5 1.5B, DeepSeek R1 Distill Qwen 1.5B, and SmolLM2.
- **📲 Accessibility & Restricted Settings Assistant:**
  - Clear guide dialog to seamlessly allow Accessibility on Android 13 & 14+.

---

## 📲 How to Install & Configure

1. **Download:** Tap the download button above or grab `DroidPrefect.apk` from the latest release.
2. **Open APK:** Once downloaded, tap the notification or open the APK from your browser / Files app.
3. **Allow Installation:** If prompted by Android (*"For your security, your phone is not allowed to install unknown apps from this source"*):
   - Tap **Settings** in the popup.
   - Toggle **"Allow from this source"** ON.
   - Tap **Back** and select **Install**.
4. **Android 13/14/15 Restricted Settings (Crucial for Sideloaded APKs):**
   - If Android greys out Accessibility or SMS with *"Restricted setting"*:
   - Open your phone's **Settings > Apps > Droid Prefect**.
   - Tap the **3 dots (⋮)** in the top-right corner.
   - Select **"Allow restricted settings"** and confirm with your PIN or fingerprint.
   - Return to Droid Prefect and enable **Accessibility**.
5. **Launch & Automate:** Open **Droid Prefect**, choose between 100% offline On-Device AI or your preferred cloud LLM, and start automating your device!

---

## 🔄 Built-In Over-The-Air (OTA) Updates

Droid Prefect features an **automatic in-app update engine**:
- Whenever a new version is released, the app will automatically notify you with an **Update Available** popup.
- You can download and install new updates directly from **Settings > About > Check for Updates** without needing to manually revisit this repository.
- Every update is verified via **SHA-256 checksum** before installation to guarantee authenticity and security.

---

## 🛡️ Privacy & Security Architecture

- **Zero Cloud Leaks:** Your chat memories, habits, and knowledge graphs stay encrypted on your device.
- **Hardware Encryption:** Sensitive API keys are protected using Android Keystore (AES-256-GCM) with hardware TEE/StrongBox.
- **Zero ADB Extraction:** `allowBackup="false"` prevents USB extraction and cloud data exfiltration.
- **Strict HTTPS / TLS 1.3:** Enforced network security config blocking cleartext transmissions.

---

## 💬 Support & Issue Reporting

For questions, feature suggestions, or bug reports, please open an issue in the [Releases Issues Tracker](https://github.com/damodp3-stack/Droid-Prefect-Releases/issues).
