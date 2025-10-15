## 📘 `payload-sandbox/README.md`

## 🧪 Payload Sandbox

A curated collection of offensive payloads for XSS, SQLi, LFI, and SSTI testing. Includes a local HTML test harness for safe injection testing.

---

## 🔧 Contents

| File | Description |
|------|-------------|
| `xss_payloads.txt` | DOM-based and reflected XSS payloads. |
| `sqli_payloads.txt` | Boolean, union, and authentication bypass payloads. |
| `lfi_payloads.txt` | Linux and Windows file traversal payloads. |
| `test_harness.html` | Local HTML page for testing payloads in browser. |

---

## 🚀 Usage

- Load `test_harness.html` in a browser and inject payloads manually.
- Use payload lists in Burp Suite, browser dev tools, or CLI fuzzers.
- Adapt payloads for lab targets or custom web apps.

---

## 🧠 Notes

- All payloads are sanitized and safe for offline testing.
- Designed for TryHackMe, PortSwigger labs, or local VMs.
- Expand with SSTI, RCE, or CSRF payloads as needed.
