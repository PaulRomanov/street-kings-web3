# 🏙️ STREET KINGS

**STREET KINGS** is an ambitious location-based MMO strategy game. Players capture real-world urban territories, expand their influence, and battle for the title of "King of the Streets" using an interactive world map.

🔗 **Project Demo:** [https://street-kings.vercel.app/](https://street-kings.vercel.app/)

---

## 🚀 Key Features

- **Real-time Geolocation Map:** Full-screen interactive map powered by [Mapbox GL JS v3](https://www.mapbox.com/mapbox-gl-js), synced with your real-world position. 🏹
- **Hexagonal Grid Intelligence:** A custom grid system dividing the world into tactical sectors using [h3-js](https://h3geo.org/). 🗺️
- **Living World (AI Bots):** Dynamic bot factions that expand their territory, providing challenges for new players. 🤖
- **Web3 Economy & Support:**
  - **Crypto Payments:** Integrated BNB and USDT (BSC) payments for IP packages. 💸
  - **Support System:** Custom donation system to support development using crypto. ☕
  - **Secure Verification:** Backend transaction validation via Supabase Edge Functions. 🛡️
- **Achievements & Badges:** A full system of passive and active achievements with unique icons and progression tracking. 🏅
- **Vast Customization:**
  - **Physical Appearance:** Faction colors and patterns (stripes, dots, waves, etc.) for territories. 🎨
  - **Refined Profile:** Optimized UI with dedicated appearance and settings sub-pages.
- **Communications Hub:**
  - **Global Frequency:** Real-time global chat with moderation tools.
  - **Encrypted DMs:** Private messaging system with organized "Mailbox".
  - **Intel Alerts:** Real-time feedback via email (powered by Resend). 📧
- **Admin Command Center:** Powerful admin panel for user management, achievement control, and game balancing. 🕹️
- **Multi-language Support:** Fully localized in **English**, **Russian**, and **Serbian**. 🌍

## 🛠 Tech Stack

- **Framework:** [Nuxt 4](https://nuxt.com/) (Vue.js 3 Composition API, Script Setup)
- **State Management:** [Pinia](https://pinia.vuejs.org/)
- **Backend & DB:** [Supabase](https://supabase.com/) (PostgreSQL + Realtime + RLS + Edge Functions)
- **Web3 / Crypto:** [ethers.js](https://docs.ethers.org/), [Reown Web3Modal](https://reown.com/w3m)
- **Maps API:** [Mapbox GL JS v3](https://www.mapbox.com/mapbox-gl-js)
- **Grid System:** [h3-js](https://h3geo.org/)
- **Notifications:** [Resend](https://resend.com/)
- **Styles:** SCSS (SASS) with a modular variable system and BEM methodology.
- **Architecture:** [Feature-Sliced Design (FSD)](https://feature-sliced.design/)

---

## 📂 Project Structure (FSD)

The project architecture ensures maximum scalability and clean code separation:

- `src/app` — Global initialization, plugins, and global styles.
- `src/pages` — Game screens and routing.
- `src/widgets` — Large self-contained UI modules (`TheMap`, `ChatWidget`, `ShopModal`, `AdminPanel`).
- `src/features` — User scenarios (Auth, Capture, Payment Flow, Profile Updates).
- `src/entities` — Business logic and state for core domain objects (Zones, User, Achievements).
- `src/shared` — Reusable toolkits, UI components, API clients, and utilities.

<img width="488" height="964" alt="image" src="https://github.com/user-attachments/assets/16a5627e-02be-4627-ba87-e8829c5a8c93" />

<img width="488" height="962" alt="image" src="https://github.com/user-attachments/assets/a6f7acbd-25fd-4f63-aca3-f81befc62865" />

<img width="498" height="969" alt="image" src="https://github.com/user-attachments/assets/6b9de00c-2ffb-4ae6-bcd3-a0048dc5131a" />

<img width="487" height="958" alt="image" src="https://github.com/user-attachments/assets/e50c3341-52cf-4afc-9a93-f251d348330a" />



