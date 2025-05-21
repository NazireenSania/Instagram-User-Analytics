# 📱 Instagram User Analytics – SQL Project using MySQL Workbench

This project simulates an Instagram-like database (`ig_clone`) and performs user interaction analysis using SQL. The analysis is divided into **Marketing Insights** and **Investor Metrics**, aiding product growth and engagement strategies.

---

## 📦 Project Overview

- 🧰 **Tech Stack**: MySQL Workbench  
- 🗂 **Database Name**: `ig_clone`  
- 🧮 **Tables**: `users`, `photos`, `comments`, `likes`, `follows`, `tags`, `photo_tags`  
- 📄 **File Structure**:
  - `Instagram User Analytics.sql` – Database schema + seed data
  - `Instagram User Analytics.pptx` – Project summary & visual slides

---

## 🧠 Project Goals

1. **Marketing Analysis** – Reward loyal users, re-engage inactive users, launch ad campaigns.
2. **Investor Metrics** – Quantify engagement, retention, and content virality.

---

## 🛠️ Database Schema

### Key Tables:

- **users** – Stores user details
- **photos** – Photo metadata with user reference
- **comments** – User comments linked to photos
- **likes** – Many-to-many: users who liked photos
- **follows** – Follower-followee relationships
- **tags** – Hashtags
- **photo_tags** – Junction table for many-to-many (photos ↔ tags)

📌 Foreign key constraints maintain relational integrity.

---

## 🔍 Sample Analytical Queries

### 📈 Marketing Analysis

- **Identify loyal users**:  
  Users who liked *every* photo.
- **Inactive users**:  
  Users who posted 0 photos.
- **Top 5 hashtags**:  
  Most used tags for campaign strategy.
- **Ad campaign timing**:  
  Determine the day with the highest user signups.

### 💼 Investor Metrics

- **Avg posts per user**
- **User growth trends**
- **Photo virality**:  
  Most liked photo with owner details.
- **Bot detection**:  
  Users who liked every photo (suspicious engagement pattern).
