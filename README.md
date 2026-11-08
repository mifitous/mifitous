# Hi, I'm Michael Fitoussi 👋

Senior System Architect & DevOps Director · 25+ years building and shipping software across web, iOS and Android, from CI/CD and platform engineering to app-store releases.

Outside of work, I build apps that put technology in the service of Jewish life.

---

## ⭐ Featured projects

> The source code of these projects is private. The live products are linked below.

### 🗺️ JewishTraveler: worldwide eruv map
**Live:** [mfitoussi.org](https://mfitoussi.org/)

An interactive map of eruvin around the world, with the current status of each one and search.
- Collects status updates from each eruv committee's own public sources and shows where every status came from and when it was last confirmed
- Runs without a server: scheduled GitHub Actions jobs run the data collection (GovMap Israel, OpenStreetMap) and publish a static JSON catalogue
- Native iOS app plus a web map

`Swift` `iOS` `JavaScript` `GitHub Actions` `OpenStreetMap`

---

### 🌙 Niddah: halachic cycle tracking
**Live:** [niddah.org](https://www.niddah.org/)

A cycle-tracking app that combines menstrual health data with halachic calculations: niddah status, seven clean days, separation days (onot) and mikvah timing, shown clearly and calculated accurately.
- One TypeScript codebase for the web (React + Vite) and mobile (Expo, iOS + Android)
- Supabase backend, EAS build and release workflows, Hebrew-first localization

`TypeScript` `React` `Expo` `React Native` `Supabase` `EAS`

---

### 🌱 My Character Coach: personal mussar mentor on WhatsApp
**Live:** [my-character-coach.vercel.app](https://my-character-coach.vercel.app)

A daily WhatsApp companion for *avodat ha-middot* (character development). Each morning it sends a check-in, picks a passage from classic mussar books (Mesillat Yesharim, Chovot HaLevavot, Orchot Tzaddikim, Rav Kook and more) that fits the reply, and tracks progress over time.
- Next.js on Vercel with a scheduled job, Meta WhatsApp Business API webhooks
- Google Gemini chooses the passage and the daily plan; Supabase (Postgres + Realtime) feeds a live dashboard
- Passages rated highly come back at intervals so they stick

`TypeScript` `Next.js` `Supabase` `Gemini` `WhatsApp API` `Vercel`

---

## 🛠️ Core skills
CI/CD · GitLab & GitHub Actions · Kubernetes / AKS · Terraform · Jenkins · iOS & Android release engineering · TypeScript · Swift
