# Vyravo AI — Demo for Dr. Sanjay Sonar Laparoscopy and Scopy Center

**Live Sales Demo v2.0** | Premium Healthcare SaaS Prototype

> **DEMO ENVIRONMENT** — All data is synthetic. Not connected to hospital systems, WhatsApp API, CRM, or medical records. For sales demonstration only.

### 🎯 Positioning
> Every enquiry gets an immediate response.
> Every qualified lead is captured.
> Every follow-up is tracked.
> Your team knows what needs attention.

### ✨ v2.0 Features (9.5/10)
- ✦ **Guided Tour** — Spotlight overlay, 5 steps, 2-min walkthrough
- 🔔 **Notification Center** — Bell with live push on new lead / assignment
- 💬 **WhatsApp (Demo) Channel** — Green bubbles, W badge, filter tabs
- हि **Hindi Toggle** — EN/हि in patient chat, Hinglish responses
- 📅 **Calendar Booking Mock** — Click any preferred date → calendar modal
- 📈 **Enhanced SVG Analytics** — Line chart + channel breakdown
- ⚡ **Instant AI Response** — <2s, no medical diagnosis, emergency escalation

### 🚀 Quick Start

**Local:**
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

**Demo Flow (5-10 min):**
1. Click **✦ Start Guided Tour** (sidebar) — 2 min overview
2. Click **▶ Run Live Demo** → patient chat opens bottom-right
3. Toggle **हि** for Hindi mode
4. Send: `Hello, I would like to know about consultation for laparoscopic surgery.`
5. Follow prompts: Name → Phone → Date → skip (email)
6. Watch toast + 🔔 bell badge bounce → new lead in dashboard
7. Go to **Conversations → WhatsApp filter** → green bubbles
8. Click any **Preferred Date** → calendar modal
9. **Assign to Staff** → follow-ups stop, notification pushed
10. Check **Analytics** → SVG chart + channel breakdown

### 📁 Structure

```
├── index.html          # Complete demo (single-file, Tailwind CDN)
├── DEMO_SCRIPT.md      # v1 script
├── DEMO_SCRIPT_V2.md   # v2 script with tour, WhatsApp, Hindi, calendar
└── README.md           # This file
```

### 🏥 Client
**Dr. Sanjay Sonar Laparoscopy and Scopy Center**
Pune, Maharashtra — Demo account

### 🛡️ Safety
- No medical diagnosis / treatment recommendations
- Emergency keywords (chest pain, bleeding, etc.) → escalation to 108 / emergency dept notice
- All patient data synthetic (DEMO DATA labels everywhere)
- No real integrations — mocked for sales demo

### 💰 Pricing (for internal sales, NOT in demo UI)
- **Starter:** Rs. 8,999/mo + Rs. 18k setup
- **Growth (Recommended - v2):** Rs. 16,999/mo + Rs. 32k setup | Annual Rs. 1,62,000
- **Premium:** Rs. 26,999/mo + Rs. 55k setup + WhatsApp API at cost

### 🔧 Tech
- Single-file frontend, Tailwind CDN, vanilla JS
- In-memory data layer (LEADS, FOLLOWUPS, NOTIFICATIONS) — easy to replace with API
- Clean architecture for future: `/api/leads`, `/api/followups`, WhatsApp Business API
- No build step, no dependencies

### 📝 Notes
- Built for Vyravo AI — Intelligent Automation for Modern Businesses
- Tagline: Intelligent Automation for Modern Businesses
- Demo built: 2026-09-08, Pune
- v2.0 — Guided tour ready, notification center, WhatsApp styling, Hindi toggle, calendar mock

---
**Vyravo AI Demo** — v2.0 • Demo Mode • All data synthetic
