# KhaoEzy 🌿 — Farm-to-Table Indian Meal Subscription Platform

**KhaoEzy** is a chef-crafted, farm-to-table weekly meal subscription and clinical nutrition web application tailored for Delhi NCR. It delivers cryo-sealed, organic Indian recipes in refrigerated, zero-waste returnable insulated totes.

---

## ✨ Key Features

### 1. Weekly Chef Menu & Interactive Recipe Viewer
* **9 Authentic Indian Chef Recipes**:
  * Organic Paneer Bhurji & Roti
  * Soya Chunks Masala Bowl
  * Dhaba Style Egg Curry
  * Shahi Veg Pulao & Raita
  * Farm-Fresh Palak Paneer
  * Desi Ghee Arhar Dal Tadka
  * Pahari Red Masoor Dal
  * Crispy Medu Vada & Sambar
  * Homestyle Aloo Gobhi Adraki
* **Dual-View Recipe Modal**:
  * **Interactive Ingredients & Spices View**: Full breakdown of whole spices, aromatics, gravies, and tempering.
  * **Infographic View**: Visual step-by-step cooking slide cards.

### 2. Streamlined Clinical Dietary Goals & Live Macro Accumulator
* **1-Click Clinical Dietary Presets**:
  * **Balanced**: Wholesome distribution of lean protein, aged grains, and farm greens.
  * **High-Protein (>180g)**: Re-weights box for athletic recovery.
  * **Low-GI Diabetic Friendly**: Unpolished lentils and low-glycemic greens for steady glucose response.
  * **Pure Satvik**: 100% onion- and garlic-free, prepared with Vedic hing and jeera.
  * **Gut Health**: Pro-digestive mountain lentils with probiotic curd raita and light tempering.
* **Live Weekly Macro Accumulator Bar**:
  * Dynamically computes **Total Box Calories**, **Average Calories per Meal**, **Protein (g)**, **Complex Carbs (g)**, and **A2 Vedic Ghee & Healthy Fats (g)** in real-time as dishes are swapped.

### 3. Interactive Box Swapper & Add-On Pantry Shelf
* **Full 9-Dish Box Swapper**: Click "Swap" on any slot to replace it with any recipe from the chef menu.
* **Farm Harvest Add-On Pantry Shelf**: Add pantry essentials like *A2 Gir Cow Bilona Ghee*, *Kachi Ghani Mustard Oil*, *Immunity Kadha Elixir*, and *Artisanal Khapli Rotis* directly into your chilled tote.

### 4. Zero-Waste Returnable Insulated Totes
* **Deposit & Green Credits**: Earn **₹50 Green Credit** per returned insulated tote box.
* **Driver Pickup Toggle**: One-click instruction for the delivery partner to collect empty boxes on arrival.

### 5. Downloadable Certified Health & Farm Manifest
* **Official Laboratory Certificate**: Itemized nutritional breakdown for the 8 selected meals.
* **Testing Clearance**: FSSAI / NPOP Green Pass and NABL-certified **0.00 PPM chemical & pesticide residue clearance**.
* **Print / PDF Ready**: Dedicated `@media print` styling for generating official reports.

### 6. Authentic Internet-Standard Weekly Subscription Plans
* **Household Toggle**: Switch between **2 People (Couples & Households)** and **1 Person (Individual & Workweek)**.
* **4 Realistic Tiers**:
  * **Weekday Starter** (6 Meals / Week) — ₹1,799 / wk (₹299 / meal)
  * **Classic Couples Box** (8 Meals / Week) — ₹2,199 / wk (₹274 / meal) • *Most Popular (Save 8%)*
  * **Workweek Complete** (10 Meals / Week) — ₹2,599 / wk (₹259 / meal) • *Save 13%*
  * **All-Week Health Reset** (14 Meals / Week) — ₹3,299 / wk (₹235 / meal) • *Save 21%*
* **Dynamic Hover & Selection**: Interactive cards with live synchronization across summary card, checkout modal, and dashboard.

### 7. Simulated UPI Checkout & Cold-Chain Delivery Tracking
* **Delhi NCR Gate Instructions**: Specify tower desk drop-off, WhatsApp gate call, silent delivery, or tote return.
* **Real-Time 5-Step Delivery Lifecycle**:
  1. Order Confirmed & Farm Dispatched
  2. Chef Hand-Braised in Kitchen
  3. Inspected & Chilled in Insulated Tote
  4. Out for Delivery with Live Driver Card
  5. Delivered at Doorstep
* **Audio & Visual Celebration**: Native Web Audio API two-tone chime and physics-based particle confetti when delivered.
* **Vacation Pause Mode**: Pause weekly deliveries for 1 week, 2 weeks, or custom dates without losing subscription discounts.

---

## 🛠 Tech Stack

* **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript (ES6+)
* **Audio**: Native Web Audio API (`AudioContext` synthesizer)
* **Visual Effects**: HTML5 Canvas particle system
* **Fonts & Icons**: Google Fonts (`Epilogue`, `Plus Jakarta Sans`), Google Material Symbols Outlined
* **Storage**: Browser `localStorage` for state persistence

---

## 🚀 Getting Started

No build tools or bundlers required. Run with any local HTTP server:

```bash
# Python
python -m http.server 3000

# Node.js
npx serve .
```

Open `http://localhost:3000` in your web browser.

---

## 📁 Repository Structure

```
KhaoEzy/
├── index.html        # Main single-page application
├── images/           # High-resolution dish photos and recipe infographics
│   ├── dish_*.jpg
│   └── recipe_*.jpg
├── .gitignore        # Git ignore rules
└── README.md         # Documentation
```

---

## 📄 License

MIT License. Crafted with 💚 for clean, healthy eating.

