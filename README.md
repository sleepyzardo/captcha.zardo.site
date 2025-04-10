# 🧠 Pokétwo CAPTCHA Solvers

Welcome to the most efficient and privacy-focused CAPTCHA solving service designed specifically for **Pokétwo**.  
Say goodbye to endless manual CAPTCHA entries and let our system handle it for you with speed, security, and reliability.

---

## 🔥 Features

- 🌩️ **Cloudflare & reCAPTCHA v2 Support**  
  We handle the most challenging CAPTCHA systems so you don’t have to.

- ⚡ **Fully Automated**  
  Submit your request, sit back, and let our system work its magic.

- 🧪 **State-of-the-Art Technology**  
  Built on advanced solving algorithms and optimized for real-time efficiency.

- 🔒 **Privacy First**  
  **No logging** of your tokens or data. Ever. Your privacy is our top priority.

- 🛡️ **Top-Class Error Handling**  
  Our system is designed to recover gracefully from issues and deliver consistent results.

- ⏱️ **Fast CAPTCHA Solving Times**  
  We solve CAPTCHAs quickly to help you maintain performance and responsiveness.

- 📦 **Frequent Security Updates**  
  Stay protected with ongoing patches for new changes and threat models.

- 💰 **Affordable Pricing**  
  Just **$0.50 per 100 solves** — get premium performance without premium prices.

- 🎮 **Dominate the Virtual Playground**  
  Whether you're grinding or collecting, do it all without getting slowed down by CAPTCHAs.

---

## 🚀 How It Works

1. **Create a Task**  
   Send us your Discord user ID and token.

2. **Get the Result**  
   Poll the result endpoint and receive the solved CAPTCHA.

---

## 📦 API Endpoints

- `POST /api/createTask` → Start a CAPTCHA task  
- `POST /api/getTaskResult` → Retrieve the solution

---

## 📜 Example Python Usage

```python
import requests

# Step 1: Create a CAPTCHA task
task = requests.post("https://captcha.zardo.site/api/createTask", json={
    "key": "your_api_key",
    "data": {
        "uid": "your_discord_user_id",
        "token": "your_discord_token"
    }
}).json()

# Step 2: Get result
result = requests.post("https://captcha.zardo.site/api/getTaskResult", json={
    "key": "your_api_key",
    "taskId": task["taskId"]
}).json()
```

## 📞 Contact & Support

For personalized plans and bulk purchases, reach out to us at **@dependential** on Discord.
We typically respond in **under 12 hours** — because your success is our mission.

## 🌐 Get Started

Visit [captcha.zardo.site](https://captcha.zardo.site) to start solving CAPTCHAs like a pro.
