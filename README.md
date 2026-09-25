# Terry Madigan | Product & AI Portfolio

**Dublin, Ireland** · Product management · Solutions architecture · Applied AI · Technical pre-sales
**Contact:** terry@vr.ie · [LinkedIn](https://linkedin.com/in/terry-madigan-43117618)

I run **VRIM**, an AI consultancy and product studio, after three startup cycles (Systemlink, VR.ie, VRIM).
20+ years shipping in regulated telco, smart energy, immersive media and, lately, production LLM products.
I work hands-on in the code: native mobile, web, backend, infra and embedded.

> **About the source code:** most product repos are private (commercial IP and client work).
> This page is the public index: live products, architecture summaries, and demo or read access on request.

---

## Shipped products

| Product | Link | What it is |
|---------|------|------------|
| **RoundCaddy** | [roundcaddy.com](https://roundcaddy.com) | Strokes-gained golf analytics on web, iOS, Android and Apple Watch |
| **BeatDeck** | [beatdeckapp.com](https://beatdeckapp.com) · [App Store](https://apps.apple.com/app/beatdeck/id6770398459) · [Google Play](https://play.google.com/store/apps/details?id=com.beatdeck.app) | Music timeline party game, native on both platforms, 28 languages |
| **Scoilius** | [scoileus.com](https://scoileus.com) | Bilingual Irish primary-school platform with ADHD, autism and dyslexia support strands |
| **SafeFamily** | [Status page](https://github.com/TerVRI/safefamily-status) | ISP-grade DNS parental controls and child-safe AI chat |

---

## Product snapshots

### RoundCaddy
GPS shot tracking, course map overlays built from OpenStreetMap data, a coach portal, and weather-adjusted distances.
Turborepo monorepo sharing one data model across four clients.
**Stack:** Next.js · SwiftUI / watchOS · Kotlin · Supabase (Postgres, Edge Functions) · Vercel · GitHub Actions

### BeatDeck
Native iOS and Android party game with global leaderboards, localised store listings in 28 languages, and production crash and product analytics.
**Stack:** SwiftUI · Kotlin / Jetpack Compose · Next.js (web) · Supabase · PostHog · Sentry · fastlane · TestFlight / Play internal testing

### Scoilius
UDL lesson modes, tiered Wave 1/2/3 supports, an AI tutor with voice, 3D and computer-vision activities, and offline-capable PWA delivery.
**Stack:** Next.js · Supabase · Vercel AI SDK · OpenAI · Anthropic · Gemini · ElevenLabs · MediaPipe · Three.js · Upstash · Stripe · Vitest + Playwright

### SafeFamily
Child online safety platform with three parts:
- **Network-level parental controls** that ISPs offer their customers, enforced at DNS level on every device in the home
- **Graduated Freedom Model**: controls that loosen as a child grows (ages 8 to 18), so trust is earned and not just switched off at a birthday
- **SafeFamily Verify**: privacy-preserving age verification, where proof of age is checked without handing over identity documents

Plus parent and child apps on iOS and Android, and a child-safe AI chat.
**Stack:** TypeScript · Go · Kotlin (Ktor) · Swift · Next.js · Docker · Kubernetes · Postgres · Redis · ClickHouse

### TourPro
Operations for touring professionals: show settlements and P&L, flight and hotel booking via Duffel, Xero export, crew logistics, and offline sync on mobile.
**Stack:** Next.js · Capacitor (iOS/Android) · Supabase · Dexie (IndexedDB) · Stripe · Xero API · Duffel API · Google Maps · Anthropic · Vercel

### IPTeeVee
A player for personal IPTV libraries (users bring their own lawful sources) on every screen: iPhone, iPad, Mac, Apple TV, Vision Pro, Android, Google TV, Fire TV and web.
A shared Rust core handles parsing, EPG, search and sync models so each native client stays thin.
**Stack:** Rust · Axum · SwiftUI / AVPlayer · Jetpack Compose / Media3 · React + hls.js · Docker

---

## Client and confidential work

Some of my current work is under NDA. I can share the stack, not the client or the specifics.

**Full-stack web platform for a client.**
**Stack:** TypeScript · Node 24 · React · Leaflet · SQLite / Postgres · JSON Schema (Ajv) · esbuild · Playwright + axe accessibility tests · Docker

**Also under NDA:** AI tooling for enterprise clients.

---

## R&D and side builds

| Project | Focus | Stack |
|---------|-------|-------|
| **R2BotBert** | Quiet AI archivist for Signal groups: summaries, decisions, todos, search. Pluggable models including local-only | TypeScript · BullMQ · Drizzle · Postgres · Docker |
| **HomeAuto** | Local-first smart home: Hue, Sonos, Zigbee and cameras behind one app | Home Assistant on Raspberry Pi · Expo · Zigbee2MQTT · go2rtc |
| **Krib** | Cloud control for the Systemlink / AquaEko heating system with voice assistants and a watch app | Node.js · Postgres · Caddy · ESP32 · Alexa / Google Home |
| **ESP32 radar** | Wi-Fi and BLE device radar: handheld TFT scope plus a multi-node floor-plan dashboard | C++ (ESP-IDF / Arduino) · ESP32-C3 · JavaScript |
| **Hammer** | Late-night "don't send that text" lock with an animated takeover | Swift (Screen Time API) · Kotlin (Accessibility) · React + Vite |
| **Looking Glass** | Holographic AI docent: speech in, LLM persona, voice and lip-sync out | ASR · LLM · TTS |
| **CounselGraph** | Grounded Irish legal search with citations | Python · RAG |
| **SpecTism** | Structured autism research tooling and dataset pipelines | Python |
| **Orbit** | Privacy-first personal memory and action agent | TypeScript monorepo |
| **ClearVolunteer** | Civic-tech prototype for reusable volunteer vetting profiles | TypeScript |

---

## Enterprise & security background

| Area | Evidence |
|------|----------|
| **Telco / government** | Ericsson Lawful Intercept: patented identity routing (US8897809B2); EMEA tier-one operator rollouts |
| **Smart energy** | Systemlink: Heat Genie (IE S86946), AquaEko/Krib (US10527297B2) |
| **Certification** | CISSP · BEng Electronic Engineering, UCD |
| **Policy** | Contributor, Ireland National AI Skills Report (CCIS AI Working Group) |

**Patents (inventor):** Ericsson LIS · Systemlink Heat Genie · Systemlink AquaEko/Krib

---

## Stack

**Languages:** TypeScript · Python · Swift · Kotlin · Rust · Go · C++ · SQL
**Web:** React · Next.js · Vite · Tailwind · Three.js
**Mobile:** SwiftUI (iOS, watchOS, tvOS, visionOS) · Jetpack Compose · React Native / Expo · Capacitor
**Backend & data:** Node.js · Axum · Supabase · Postgres · Redis · ClickHouse · SQLite · BullMQ · Drizzle
**Infra:** Docker · Kubernetes · Hetzner · Vercel · AWS · GCP · Caddy · GitHub Actions · fastlane
**AI:** Claude · OpenAI · Gemini · OpenRouter · local models · RAG · evaluation harnesses · ElevenLabs · MediaPipe
**Quality & ops:** Playwright · Vitest · axe · Sentry · PostHog · Upptime
**Hardware:** ESP32 · Raspberry Pi · Home Assistant · Zigbee
**How I build:** Cursor · Claude Code · agent-driven workflows with human review on every change

---

## Public repos

| Repo | Description |
|------|-------------|
| [safefamily-status](https://github.com/TerVRI/safefamily-status) | SafeFamily uptime monitoring (Upptime) |
| [esp32-radar-upstream](https://github.com/TerVRI/esp32-radar-upstream) | Fork of a handheld ESP32 Wi-Fi/BLE scope |

Private repos (demo or read access for interviews): `golfstats` · `safefamily` · `TourPro` · `Rang4mentor` · `ipteevee`

---

*Last updated: September 2026 · Portfolio index for [github.com/TerVRI](https://github.com/TerVRI)*
