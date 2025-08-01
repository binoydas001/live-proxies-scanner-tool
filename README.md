# live-proxies-scanner-tool
this live-proxies-scanner tool is open-source and simple tool based on pythonsit designed to extract the live proxy from headless proxy website. 

## 🚀 Features

- ✅ **Beautiful TUI (Terminal User Interface)** with Rich
- 🌐 **Scrapes multiple proxy list URLs** (custom input)
- 🧪 **Validates proxies (SOCKS4/5 & HTTP)** using `curl`
- 🌍 **GeoIP Lookup** for each proxy (country flags)
- ⚡ **Latency measurement** (speed in ms)
- 📁 **Saves valid and dead proxies** to separate files
- 🔁 **Auto-refresh scan loop** every 10 seconds
- 📦 **Fully asynchronous + subprocess-based design**

---

## 📸 Screenshot

╔══════════════════════════════════════════════════╗
║ 🕵️ PROXY SCANNER TOOL — BINAY DAS ║
╚══════════════════════════════════════════════════╝

[✔] Initializing Proxy Scanner Engine...
[✔] Loading Proxy Sources...
[✔] Checking Internet Connection...
[✔] Preparing UI Interface...
[✔] Fetching Geo & Latency Data...

────────────────────────────────────────────────────
░░ SCANNER STATUS ░░
────────────────────────────────────────────────────

IP:PORT TYPE STATUS COUNTRY SPEED
1 104.244.76.13:8080 HTTP 🟢 VALID 🇺🇸 US 172ms
2 142.250.195.206:80 SOCKS5 🟢 VALID 🇳🇱 NL 201ms
3 185.199.108.153:3128 HTTP 🔴 DEAD -- --

📁 Valid proxies saved to: results/valid.txt
🪦 Dead proxies logged in: results/dead.txt
🔁 Auto-refreshing every 10 seconds...
✋ Press Ctrl+C to stop the scan

yaml
Copy
Edit

---

## 🛠 Requirements

- Python 3.10+
- `curl` installed (for proxy validation)
- GeoIP tool (`geoiplookup`) for country detection

### Install dependencies:

```bash
pip install rich requests
sudo apt install curl geoip-bin
💡 Usage
bash
Copy
Edit
python3 proxy_scanner.py
Then enter one or more proxy list URLs separated by commas (,) when prompted.
The scan will begin and update in real-time.

📁 Output Files
results/valid.txt — contains valid proxies with type, speed, and country

results/dead.txt — logs all unreachable/dead proxies

🧠 Technologies Used
Rich — for beautiful terminal tables, colors, and panels

asyncio — for async processing and performance

subprocess + curl — for real-world proxy testing

geoiplookup — to detect country from IP

📜 License
This project is licensed under the MIT License.
See LICENSE for more details.

👨‍💻 Author
Made with 💻 and ☕ by Binoy Das

🔗 GitHub | 📧 binoy@example.com

🤝 Contributing
Pull requests, feature suggestions, and proxy source improvements are welcome!

To contribute:

Fork this repo

Create a new branch

Submit a pull request 🚀

⚠️ Disclaimer
This tool is for educational and research purposes only.
The author is not responsible for any misuse.

vbnet
Copy
Edit

Let me know if you want me to:
- Generate a `README.md` file directly
- Include animated demo GIFs or badges
- Add auto-flag sorting (e.g., 🇺🇸 > 🇮🇳 > 🇧🇷) in future version notes








Ask ChatGPT
