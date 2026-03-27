# 🐾 PetConnect — Tucson's Lost & Found Pet Alert System

> **Real-time lost pet alerts for Tucson's East Side (85710)**  
> Built by Lamar Myers · VTREI LLC · Tucson, Arizona

---

## What It Does

PetConnect is a free community app for Tucson's East Side that helps neighbors find lost pets, report found pets, and flag stray sightings — all in real time.

The moment someone posts a lost or found pet, every nearby user receives a **P.A.W.S. Alert** — a full-screen notification that fires like an Amber Alert, with the pet's name, photo, and last known location spoken aloud.

---

## Features

| Feature | Description |
|---|---|
| 🚨 **P.A.W.S. Alert** | Full-screen Amber Alert-style notification fires instantly on new posts |
| 📍 **GPS Location** | Reverse-geocodes coordinates to human-readable Tucson addresses |
| 🎤 **Voice-to-Text** | Post a lost pet by speaking — no typing required |
| 📸 **Photo Upload** | Upload a pet photo directly from your phone |
| ✅ **Verified Claim Flow** | Only the real owner can mark a pet as reunited |
| 🗺 **Safe Meetup Spots** | Built-in list of safe public handoff locations (police stations, Walgreens) |
| 📢 **Report Suspicious Activity** | Flag suspicious claims, saved to Supabase + email notification |
| 🌙 **Dark & Light Mode** | Two themes, both mobile-first |

---

## The Three Post Types

- **Lost a Pet** — Post your missing pet with photo, description, and GPS location
- **Found a Pet** — Post a pet you found so the owner can claim them
- **Spot a Stray** — Flag a stray sighting with location; someone nearby may recognize them

---

## Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript — single-file app
- **Database:** Supabase (PostgreSQL)
- **Auth:** Google Sign-In (Supabase Auth)
- **Notifications:** EmailJS
- **Location:** OpenStreetMap Nominatim (free reverse geocode)
- **Voice:** Web Speech API (no third-party)
- **Hosting:** GitHub Pages / Vercel

---

## Live App

🔗 **[Launch PetConnect →](https://pethub-tucson.github.io/petconnect)**

---

## Setup (for developers)

1. Clone this repo
2. Open `index.html` in any browser — no build step required
3. For full functionality, set your own Supabase credentials:
   - Replace `SUPABASE_URL` and `SUPABASE_ANON_KEY` in the script section
   - Enable Row-Level Security (RLS) in your Supabase dashboard
   - Create the `pets` and `reports` tables (SQL in `/docs/schema.sql`)
4. For email notifications, set up an EmailJS account and add your keys

---

## Part of PetHub

PetConnect is one of three apps in the **PetHub** ecosystem:

| App | Description |
|---|---|
| 🐾 **PetConnect** | Lost & Found alerts ← *you are here* |
| 💚 **[PawMatch](../pawmatch)** | Dog playdate matching |
| 🏆 **[Paw Pound](../paw-pound)** | Community pet ratings |

---

## About

Built by **Lamar Myers** in Tucson, Arizona (85710) under **VTREI LLC**.  
This app is free, ad-free, and community-funded by time and love.

> *"Every pet deserves to find their way home."*

---

*Tucson · East Side · 85710 · Built with ❤️*
