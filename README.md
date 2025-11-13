# iimg.live — Free Permanent Image Hosting (Showcase Documentation)

iimg.live is a fast, permanent, privacy-friendly image hosting service designed for creators, students, communities, and developers who need reliable image storage without ads, accounts, or complexity.

This repository is a **showcase and documentation repo only**.  
The production backend code is private for security reasons.  
This repo explains the project, architecture, and how Cloudflare powers the platform.

---

## 🌍 Live Website
**https://iimg.live**

---

## 🚀 What is iimg.live?

iimg.live is a free, lightweight, and permanent image hosting platform.  
Users can upload images up to 8 MB and instantly get:

- Direct URLs  
- HTML embed code  
- BBCode  
- Markdown links  
- Small preview thumbnails  

The platform is built to be **fast, simple, ad-free, and reliable**, especially for users in regions where hosting costs are a barrier.

---

## 🎯 Key Features

- ⚡ **Instant uploads**  
- 🔗 **Permanent direct links** (no expiry)  
- 🖼 Supports **JPG, PNG, GIF, WebP**  
- 🆓 No registration required  
- 🔒 Privacy-friendly  
- 🪶 Lightweight frontend (HTML + PHP)  
- 🌐 Global CDN distribution  
- 🏃 Works on mobile and low-end devices  
- 📤 Thumbnail/preview link support  

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|------------|
| Storage | **Cloudflare R2** |
| CDN Delivery | **Cloudflare CDN** |
| Website | HTML + CSS + PHP |
| Image Routing | Cloudflare |
| DNS | Cloudflare |
| Optional Future | Workers, KV, Image Resizing |

iimg.live heavily uses Cloudflare infrastructure to keep the service free and sustainable.

---

## 🛠 Why Cloudflare Is Critical for This Project

iimg.live depends on Cloudflare in multiple ways:

### ✔ R2 Object Storage  
Used for permanent, scalable, low-cost image storage.  
All uploaded images and thumbnails are stored securely in R2 buckets.

### ✔ CDN Global Caching  
Direct image URLs are globally cached through Cloudflare's network for high-speed delivery.

### ✔ Zero-eTier Architecture  
The workload is light and perfect for Workers/R2-based scaling.

### ✔ Cost Optimization  
Image hosting usually has very high bandwidth costs.  
Cloudflare’s infrastructure makes it possible to keep the service **free for global users**, especially under student-budget conditions.

---

## 📚 Project Goals

- Provide a **permanent, free image host** for students, forums, developers, and small communities.
- Offer a **simple alternative** to complicated platforms.
- Keep infrastructure costs sustainable using Cloudflare’s modern stack.
- Build a privacy-friendly tool without tracking or ads.

---

## 🗺 Roadmap

### Near-Term
- Add multiple embed-format options (done)
- Improve thumbnail generation
- Add better error messages and upload status UI
- Rate-limit protection to avoid abuse

### Mid-Term
- Add optional user accounts (no email required)
- Deploy API endpoint for developers (upload via POST)
- Add Workers-based caching layer
- Explore Cloudflare Images for processing

### Long-Term
- Multi-region storage replication
- Community moderation tools
- Open-source parts of the upload workflow (safe components only)

---

## 🔒 Security & Privacy

- No user accounts required  
- No tracking or analytics  
- No sensitive data stored  
- Only images + metadata stay in R2  
- Backend code remains **private** for security reasons  

This repository is documentation-only.

---

## 📊 System Architecture (Simplified)

Clients upload → stored in R2 → served globally via CDN.

---

## 👤 Founder

**Name:** Bidyut Mondal 
**Role:** Solo Founder / Developer  
**Email:** founder@iimg.live  
**Website:** https://iimg.live

---

## 🤝 Purpose of This Repository

This repo exists to:

- Document the project  
- Showcase architecture for review  
- Apply to Cloudflare developer/startup programs  
- Share technical plans  
- Build community transparency  

The backend code remains private.

---

## 📬 Contact

If you want to collaborate, suggest improvements, or contribute ideas, feel free to reach out:

📧 **founder@iimg.live**  
🌐 https://iimg.live

---
