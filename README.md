# 🎬 AI System That Turns Podcasts into Short-Form Clips

This is a fully automated system built with **n8n**, **Vizard.ai**, **OpenAI**, **Google Sheets**, and **Gmail**.  
It converts long-form podcasts or YouTube videos into short-form, social-ready clips for **TikTok**, **Instagram**, and **YouTube Shorts**.

---

## 🔄 How the System Works

### 1. Scrape
- Uses **RSS** to check a YouTube channel for new uploads  
- Extracted video links are sent to **Vizard**, which generates vertical short clips  
- Clips are automatically queued for processing  

### 2. Generate
- Pulls clip data and transcripts from **Vizard**  
- Uses **OpenAI** to generate TikTok or Instagram-style captions  
- Stores all clip information in **Google Sheets**  
- Sends a notification email via **Gmail** once clips are ready  

---

## ⚙️ Built For
- 🎙️ Podcast creators who want to repurpose episodes  
- 📺 Media teams managing high-volume content  
- 🧠 Automation freelancers and agencies offering content systems  

---

## 📌 Why It’s Useful
- No manual editing required  
- 1 long podcast episode → **10 to 12 short-form clips**  
- Maintains consistent presence across TikTok, Instagram, and YouTube Shorts  
- Saves time and reduces reliance on editing staff  
