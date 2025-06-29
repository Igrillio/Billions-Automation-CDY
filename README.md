# Billions Network BOT - Automation by Cryptodai

Automate your **daily reward claiming** on Billions.Network using multiple accounts with proxy rotation. Built for beginners with step-by-step usage.

---

## 🔗 Register First

* **Signup Link:** [Billions Network](https://signup.billions.network?rc=2V2A7DFC)
* Signup using **Google Account**

---

## 🚀 Features

* ✅ Auto Get Account Info
* ✅ Auto Claim Daily Reward
* ✅ Auto Run with:

  * [Proxyscrape Free Proxy](https://proxyscrape.com/free-proxy-list) - `Choose 1`
  * Private Proxy - `Choose 2`
  * Without Proxy - `Choose 3`
* ✅ Auto Rotate Invalid Proxies (`y/n`)
* ✅ Multi-Account Support via `cookies.txt`

---

## 🛠️ Requirements

* Python 3.9 or higher
* pip or pip3 installed

---

## 📥 Installation (Beginner-Friendly)

1. **Clone this repository:**

```bash
git clone https://github.com/cryptodai3/Billions-Automation-CDY.git
```

2. **Navigate into folder:**

```bash
cd Billions-Automation-CDY
```

3. **Install all required Python modules:**

```bash
pip install -r requirements.txt
# or
pip3 install -r requirements.txt
```

---

## 🧾 Configuration Files

### 1. `cookies.txt` (Add your account sessions)

```
session_id=eyJhbGciOiJ... (your session ID here)
session_id=eyJhbGciOiJ... (next session)
```

### 2. `proxy.txt` (Optional for proxy run)

```
http://127.0.0.1:8080
socks5://127.0.0.1:9050
http://user:pass@ip:port
```

> ⚠️ Format must match examples above.

---

## ▶️ Run The Bot

```bash
python bot.py
# or
python3 bot.py
```

Follow on-screen questions:

* Choose proxy type (1 / 2 / 3)
* If using proxy, choose whether to rotate bad proxies (y / n)

The bot will loop through all accounts, check status, and claim daily rewards.

---

### ⚠️ Important Disclaimer

* **DYOR** – Always do your own research before using any automation tools

