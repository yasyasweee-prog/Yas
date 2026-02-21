# 🌸 Bloom — Your Personal Fitness Journey

> *A soft, beautiful, and motivating fitness tracker built for your 10kg confidence journey.*

![Bloom App](icons/icon.svg)

---

## ✨ What is Bloom?

**Bloom** is a personal fitness tracking Progressive Web App (PWA) designed for a real 90-day weight loss and confidence journey. It combines daily logging, milestone celebrations, meal planning, and motivation — all wrapped in a calming pastel aesthetic.

Built with pure HTML, CSS, and JavaScript. No frameworks, no accounts, no subscriptions. Just you and your goals.

---

## 🎯 Features

| Feature | Details |
|---|---|
| 🏠 **Dashboard** | Daily quote, challenge timeline (7→90 days), step & water rings, weight chart |
| 📝 **Daily Log** | Track weight, steps, water, sleep, workout, meals, and mood |
| 🥗 **Meal Plan** | Personalized IF plan with sattu shake recipe & protein rotation |
| 🏆 **Milestones** | 8 auto-unlocking badges from first log to goal achieved |
| ✨ **Tips** | Height, sleep, junk swaps, hydration, pilates advice |
| 📱 **PWA** | Install on phone, works fully offline |

---

## 📱 Challenge Timeline

| Challenge | Name | Goal |
|---|---|---|
| 🌱 7 Days | Spark | Build the habit |
| 🌿 14 Days | Grow | Feel the change |
| 🌸 21 Days | Habit | It's part of you now |
| 🌺 30 Days | Glow | Visible results |
| 🦋 45 Days | Transform | Halfway milestone |
| ⭐ 60 Days | Strong | New lifestyle |
| 👑 90 Days | Queen | Goal achieved! |

---

## 🍽️ Daily Meal Plan (Intermittent Fasting)

```
7:00 AM   →  700ml warm water + 1 cup green tea
11:20 AM  →  Lunch: Stir-fried veggies + protein + 1 cup rice
3:30 PM   →  Fruits or sattu-banana shake (no sugar)
After 4PM →  Fasting window (water/green tea only)
```

**Protein Rotation:** Paneer → Chicken → Soya → Eggs

---

## 🚀 Getting Started

### Option 1: GitHub Pages (Recommended)
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app will be live at `https://yourusername.github.io/bloom`

### Option 2: Run Locally
```bash
git clone https://github.com/yourusername/bloom.git
cd bloom
# Open with a local server (required for service worker)
npx serve .
# OR
python3 -m http.server 8080
```
Then open `http://localhost:8080`

> ⚠️ **Note:** Service workers require HTTPS or localhost. Opening `index.html` directly won't register the SW.

### Option 3: Install as App (PWA)
Once hosted, visit the URL on your phone and tap **"Add to Home Screen"** — it works like a native app, even offline!

---

## 📁 Project Structure

```
bloom/
├── index.html          # Main app (single-page)
├── manifest.json       # PWA manifest
├── sw.js               # Service worker (offline + caching)
├── README.md           # This file
└── icons/
    ├── icon.svg        # Master SVG icon
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

---

## 💾 Data & Privacy

All your data is stored **locally in your browser** using `localStorage`. Nothing is sent to any server. Your progress is yours alone.

> To back up your data: Open browser DevTools → Application → Local Storage → copy the `logs` key.

---

## 🌸 Milestone Badges

| Badge | Unlock Condition |
|---|---|
| 🌱 Journey Begins | Log your first day |
| 🌿 7-Day Warrior | Log 7 entries |
| 💪 First Kilo Gone | Reach 63kg |
| 🚶 Step Queen | Hit 10,000+ steps in a day |
| 🌸 14-Day Glow | Log 14 entries |
| ⭐ Halfway There | Reach 59kg |
| 🦋 30-Day Transformation | Log 30 entries |
| 👑 Goal Achieved | Reach 54kg |

---

## 🧘 Workout Plan

Inspired by **Lily Sabri's** pilates workouts:
- Lose Fast in 4 Days series
- Abs in 14 Days series
- Morning + Evening walks (target: 7,000–10,000 steps/day)

---

## 💡 Tips Included

- **Feel Taller** — Posture, sleep, calcium, stretching
- **Step It Up** — Morning + evening walk strategy  
- **Junk Food Swaps** — Makhana, roasted chana, dates
- **Hydration Hack** — 200ml before meals
- **Sleep = Weight Loss** — Growth hormone + hunger hormones
- **Pilates Power** — Consistency over intensity

---

## 🛠️ Tech Stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, animations, grid, flexbox
- **Vanilla JS** — No dependencies, pure ES6+
- **PWA** — Service worker, web manifest, installable
- **localStorage** — Client-side data persistence
- **Google Fonts** — Playfair Display + DM Sans

---

## 🎨 Design

- **Aesthetic:** Soft pastel, calm, feminine, editorial
- **Colors:** Rose `#f2a7b8` · Sage `#b5d5c5` · Lavender `#c9b8e8` · Peach `#f9c9a8`
- **Fonts:** Playfair Display (headings) + DM Sans (body)
- **Motif:** Blooming flower — growing stronger every day

---

## 📄 License

MIT License — free to use, fork, and personalize for your own journey.

---

<div align="center">

Made with 💗 for a 90-day confidence journey

*You are not a before photo. You are becoming the healthiest, happiest version of you.*

**🌸 Bloom at your own pace 🌸**

</div>
