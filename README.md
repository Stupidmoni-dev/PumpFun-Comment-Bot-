# PumpFun-Comment-Bot-
Here's the updated `README.md` with your Telegram contact as a clickable link:  

---

# **PumpFun Comment Bot** 🚀  

### **Automate Comments & Boost Engagement on Pump.fun**  

The **PumpFun Comment Bot** is a powerful automation tool designed to **post comments on Pump.fun tokens** using multiple accounts, random avatars, and varied messages. It helps crypto projects **increase engagement, visibility, and credibility** effortlessly.  

## **🔥 Why This Bot is Important**  
- **Increases Exposure**: More comments make your token look active and attract new investors.  
- **Automates Engagement**: No need to comment manually—let the bot do the work!  
- **Bypasses Repetitive Content Deletion**: Supports **randomized comments** to avoid detection.  
- **Supports Multiple Accounts**: Uses cookies to manage different accounts.  
- **Proxy Support**: Rotate IPs to prevent bans (optional).  
- **Easy Customization**: Edit comment styles, avatars, and settings.  

## **🛠 Features**  
✅ Automated Comment Posting  
✅ Multi-Account Support (via cookies)  
✅ Customizable Good & Bad Comments  
✅ Random Avatars for Natural Interaction  
✅ Token Address Customization  
✅ Proxy Support to Avoid Detection  

---

## **📌 Installation & Usage**  

### **1️⃣ Install Dependencies**  
```bash
sudo apt update && sudo apt install -y nodejs npm
npm install -g yarn
cd pumpfun-comment-bot
yarn install
npx playwright install-deps
npx playwright install
```

### **2️⃣ Build the Code**  
```bash
npm run build
```

### **3️⃣ Generate Accounts**  
Edit `NUMBER_OF_ACCOUNT` in `.env`, then run:  
```bash
npm run generate
```
This will create cookie files in `/cookies/`.  

### **4️⃣ Add Comments & Avatars**  
- **Edit comments in `/comments/`**  
  - `bad.txt` → Negative comments  
  - `nice.txt` → Positive comments  
  - Select comment type in `.env` (`COMMENT_TYPE=nice` or `bad`)  
- **Add profile pictures to `/pics/`**  

### **5️⃣ Set Token Address**  
Edit `.env` and add your target token:  
```env
TOKEN_ADDRESS=YOUR_TARGET_TOKEN
```

### **6️⃣ Run the Bot**  
```bash
npm start
```

---

## **💰 Price & Purchase**  
This bot is available for **$500**. If you're interested, contact me on Telegram:  

🔗 **[@MoonDevOnSol](https://t.me/MoonDevOnSol)**  

🚀 **Boost your Pump.fun token today!** 🚀
