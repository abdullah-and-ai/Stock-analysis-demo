# Stock-analysis-demo
Here is a clean **README.md** you can include with your project 👇

---

# 📈 Live Gold Price Tracker (XAU/USD)

This Python script fetches the **live gold price (XAU/USD)** and displays it in a **real-time updating graph** using the Twelve Data API.

It continuously retrieves the latest price and plots it against time, creating a live price feed visualization.

---

## 🚀 Features

* 🔄 Fetches live gold price using API
* 📊 Real-time updating graph
* 🕒 Timestamped price tracking
* 🖥️ Console output with current price
* 🛑 Safe exit with `Ctrl + C`

---

## 🧰 Requirements

Install required libraries before running:

```bash
pip install requests matplotlib ipython
```

---

## 🔑 API Key Setup

This script uses the Twelve Data API.

1. Create a free account at:
   👉 [https://twelvedata.com/](https://twelvedata.com/)

2. Copy your API key.

3. Replace the placeholder:

```python
API_KEY = "YOUR_API_KEY"
```

---

## ▶️ How It Works

1. Sends a request to Twelve Data for **XAU/USD** price.
2. Stores timestamp & price.
3. Updates a live matplotlib graph.
4. Prints the current price in the console.
5. Waits 60 seconds before the next request.

---

## 🧪 Run the Script

```bash
python gold_live.py
```

You will see:

* A live updating graph
* Current gold price printed every minute

---

## 📉 Sample Output

```
Live Gold Price: 2053.42 at 2026-03-02 14:30:00
```

---

## ⚠️ API Rate Limits

Free tier allows **8 requests per minute**.

This script uses **1 request per minute** to stay safe.

Modify if needed:

```python
time.sleep(60)
```

---

## 🛑 Stopping the Script

Press:

```
CTRL + C
```

You will see:

```
Live feed stopped by user.
```

---

## 🧠 Customization Ideas

You can enhance this project by:

* Tracking multiple metals (Silver, Platinum)
* Saving data to CSV
* Adding alerts when price crosses a threshold
* Creating a web dashboard
* Sending Telegram/email notifications

---

## 📜 License

Free to use and modify for educational and personal projects.

---

If you want, I can also:

✅ add **CSV logging**
✅ make it run in **Google Colab**
✅ convert it into a **desktop app**
✅ build a **web dashboard**
✅ add **price alerts**

Just tell me 🙂
