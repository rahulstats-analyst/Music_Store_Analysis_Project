
A comprehensive SQL data analysis project exploring a digital music store's database to uncover business insights, customer behaviors, and revenue trends.
<div align="center">
  <img src="https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?q=80&w=2070&auto=format&fit=crop" alt="Music Store Data Analysis Banner" width="100%">

  <h1>🎵 Music Store Data Analysis</h1>

  <p>
    <img src="https://img.shields.io/badge/Language-SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
    <img src="https://img.shields.io/badge/Skill-Data_Analysis-FF6F00?style=for-the-badge&logo=google-analytics&logoColor=white" alt="Data Analysis">
    <img src="https://img.shields.io/badge/Status-Completed-28A745?style=for-the-badge" alt="Completed">
  </p>

  > *Extracting valuable business insights, customer behavior patterns, and revenue trends from a digital music store's relational database.*
</div>

---


<div align="center">
  <img src="https://cdn.dribbble.com/users/1770290/screenshots/6183149/bg_79.gif" alt="SQL Animation Placeholder" width="600">
</div>

---

## 🗂️ Dataset Architecture

| Category | Tables (.csv) | Description |
| :--- | :--- | :--- |
| 👥 **Core Entities** | `employee`, `customer` | Internal staff and customer demographic data. |
| 🎸 **Inventory** | `artist`, `album`, `track`, `genre`, `media_type` | Full catalog of the music store's offerings. |
| 💰 **Sales Data** | `invoice`, `invoice_line` | Transactional records and financial history. |
| 🎧 **Collections** | `playlist`, `playlist_track` | Custom track groupings and user playlists. |

---

## 📊 Entity-Relationship Schema
Visualizing the complex joins and foreign key relationships used in the SQL queries.

<div align="center">
  <img src="schema_diagram.png" alt="Music Store Database Schema" width="800">
</div>

---

## 💡 Key Business Questions Unlocked

<details>
  <summary><b>Click to reveal the strategic questions answered by this project ⬇️</b></summary>
  <br>
  <ul>
    <li>🌍 <b>Global Reach:</b> Which countries generate the highest volume of invoices?</li>
    <li>💎 <b>High-Value Customers:</b> Which city boasts the best customers based on total revenue?</li>
    <li>🏆 <b>Top Spender:</b> Who is the single most valuable customer in the database?</li>
    <li>🔥 <b>Trending Sounds:</b> What is the most popular music genre dominating specific countries?</li>
    <li>🎤 <b>Artist ROI:</b> Which musicians and bands are driving the highest profits?</li>
  </ul>
</details>

---

## 🚀 Quick Start Guide

1. **Clone the Repo:** Download all the `.csv` datasets provided in this repository.
2. **Set up the Database:** Import the files into your preferred SQL environment (PostgreSQL, MySQL, SQLite, etc.).
3. **Map the Schema:** Ensure the tables are structured according to `schema_diagram.png`.
4. **Execute:** Run `Music_Store_Query.sql` to generate the insights!

---
<div align="center">
  Created by <a href="https://github.com/rahulstats-analyst">Rahul</a> • Open to collaborations and data discussions!
</div>
