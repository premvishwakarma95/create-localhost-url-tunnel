# 🌐 Local Tunnel Setup Guide (Expose Localhost to Any Device)

This guide explains how to **create a local tunnel** and get a **public URL** so you can test your local app  
(**Node.js / React / Next.js / APIs**) on **any device** like mobile phones, QA systems, or client machines.

## ⭐ Option 1: ngrok (Most Popular)
🔹 Install - Windows / macOS / Linux
```bash
npm install -g ngrok
```
OR download from official site.
###🔹 Start your app
```bash
npm start
```
Assume your app runs on `http://localhost:3000`
### 🔹 Create tunnel
```bash
ngrok http 3000
```
### 🔹 Output
```bash
Forwarding  https://a1b2c3.ngrok.io -> http://localhost:3000
```
✅ Use this URL on:
- Mobile browser
- Webhooks
- Any external service
