# 🧭 Oru Trip Pokam
### *"Shall We Go on a Trip?"*

> **Discover Hidden Places. Find Travel Partners. Explore India Together.**

A community-driven travel platform connecting travelers across India. Built entirely with HTML, CSS, and JavaScript — no frameworks, no build tools, deployable on GitHub Pages in minutes.

---

## 🌏 Live Website

🔗 [orutrippokamundo.co.in](https://orutrippokamundo.co.in)

---

## ✨ Features

### 🗺️ Explore Indian States
- All 28 States + 8 Union Territories listed as interactive cards
- Click any state to view and add **Tourist Spots**
- Each spot includes: name, category, location, description, travel info, and photo
- Spot count badge shown on each state card

### 🌟 Hidden Gems
- Community-contributed secret destinations from across India
- Add a gem with: place name, state, category, description, and **photo upload**
- Categories: Nature, Heritage, Adventure, Food, Offbeat, Beach, Mountains

### 🤝 Travel Partners
- Browse traveler profiles looking for companions
- Add your own profile with travel style, destination, bio, and contact info
- **Connect** button to reach out to fellow travelers

### 🗺️ Trip Plans
- Create and browse community trip plans
- Each trip includes: destination, dates, traveler count, description
- **Map / Location link** — paste any Google Maps link
- **Organiser contact info** — phone, email visible on the card
- **"Contact as Travel Partner"** — send a message directly to the trip organiser
- **"I'm Interested"** button for quick expressions of interest
- Open/Closed status for partner slots

### 📸 Travel Stories
- Share travel experiences with **photo uploads from your device**
- Add travel tips alongside your story
- Displayed as beautiful quote cards with author info

### 🔐 User Authentication
- **Sign Up** — create a free account
- **Login** — secure email + password login
- **Forgot Password / Reset** — password reset flow
- Logged-in user shown in navbar with avatar and logout option
- Session persists across page refreshes

### 💾 Data Persistence
- All user-added content saved via **localStorage**
- Survives page refresh and browser restarts
- No backend required

---

## 🚀 Deployment (GitHub Pages)

### Step 1 — Upload the file
1. Extract the downloaded zip
2. You'll find a single `index.html` file
3. Go to your GitHub repository
4. Upload `index.html` to the **root** of the repository

### Step 2 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**

### Step 3 — Connect your domain (optional)
1. In **Settings → Pages**, add your custom domain
2. In your domain registrar (e.g. GoDaddy, Namecheap), add these DNS records:

| Type  | Host | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | yourusername.github.io |

### Step 4 — Wait & visit
- GitHub Pages takes **1–2 minutes** to deploy
- Visit your domain or `yourusername.github.io/repo-name`

---

## ⚠️ Common Deployment Issues

| Problem | Fix |
|--------|-----|
| 404 File not found | Make sure `index.html` is in the root folder, not inside a subfolder |
| Blank white page | Clear browser cache and hard reload (Ctrl+Shift+R) |
| Wrong file name | File must be named exactly `index.html` (all lowercase) |
| Pages not enabled | Go to Settings → Pages and set source branch to `main` |
| Custom domain not working | DNS changes can take up to 24–48 hours to propagate |

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| HTML5 | Structure and layout |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | All interactivity and logic |
| localStorage | Client-side data persistence |
| FileReader API | Photo uploads from device |
| Google Fonts | Fraunces (headings) + Nunito (body) |

---

## 📁 Project Structure

```
oru-trip-pokam/
└── index.html        ← Entire website (HTML + CSS + JS in one file)
```

Single file. Zero dependencies. Zero build steps.

---

## 📱 Responsive Design

- ✅ Mobile-first layout
- ✅ Works on all screen sizes (phone, tablet, desktop)
- ✅ Touch-friendly buttons and modals
- ✅ Hamburger menu on mobile

---

## 🔮 Planned Features

- [ ] Firebase backend for real-time data sync across devices
- [ ] Image hosting via Cloudinary
- [ ] Email notifications for trip partner requests
- [ ] Search and filter destinations
- [ ] User profile pages
- [ ] Rating and review system for destinations

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*© 2025 Oru Trip Pokam — Discover Hidden Places. Find Travel Partners. Explore India Together.*
