# Vyravo AI — Sales Demo Script v2.0
**Client:** Dr. Sanjay Sonar Laparoscopy and Scopy Center  
**Type:** Interactive Frontend Prototype v2 • Guided Tour Ready  
**Duration:** 5-10 minutes (2-min tour + 5-min live flow)

## What's New in v2.0 (9.5/10)
- ✦ **Guided Tour** with spotlight overlay (5 steps)
- 🔔 **Notification Center** - bell with live push on new lead / assignment
- 💬 **WhatsApp (Demo) Channel** - green bubbles, filter tabs, W badge
- हि **Hindi Toggle** in patient chat (EN/हि) - Hinglish responses
- 📅 **Calendar Booking Mock** - click any preferred date
- 📈 **Enhanced SVG Chart** in Analytics

## Opening (30s)
> "This is v2 demo with guided tour. Everything is demo data — not connected to real systems. Let me start the 2-min tour."

Click **✦ Start Guided Tour** in sidebar or **Start Tour** in top bar.

Tour Steps:
1. **Metrics** - 100% response rate, EN/हि support
2. **Patient Chat Widget** - bottom-right, Hindi toggle
3. **Automation Flow** - 0h, 24h, 3d + bell notifications
4. **Attention + Notifications** - click bell icon
5. **Recent Enquiries + Channels** - Website + WhatsApp + Phone

## Step 1: Patient Enquiry (1 min)
- Click **▶ Run Live Demo** → chat opens
- Toggle **हि** top-right of chat to show Hindi mode
- Disclaimer changes to Hindi
- Input: "नमस्ते, लैप्रोस्कोपिक सर्जरी के लिए consultation चाहिए" or English example
- Show emergency handling: type "chest pain" or "छाती में दर्द"

## Step 2: AI Instant Response (1 min)
- AI replies <2s in selected language
- Collects: name → phone → date → email (skip)
- Quick replies adapt to language
- Show typing indicator (3 dots)

## Step 3: Lead Capture + Notification (30s)
- After completion: toast + **bell badge increments + bounces**
- Click 🔔 bell top-right → notification dropdown: "New enquiry: Rahul Kulkarni • Just now • Website Chat • EN"
- Go to Overview → Recent shows new lead with 🟢 if WhatsApp
- Open lead drawer → shows WhatsApp styling if source is WhatsApp, calendar button on preferred date

## Step 4: WhatsApp View (1 min) - NEW
- Go to **Conversations**
- Top filter: All | Website | WhatsApp | Phone
- Click **WhatsApp** → shows only WhatsApp leads (Sneha Kulkarni, Sunita Desai)
- Select Sunita Desai → background changes to WhatsApp doodle pattern, bubbles green (#DCF8C6) with ✓✓ ticks
- Explain: "In production, this would be real WhatsApp Business API — here we mock the styling to show how staff would see it"

## Step 5: Follow-up + Calendar (1 min)
- **Follow-ups** tab → shows scheduled/sent/stopped with source icons
- Click any lead's preferred date → **Calendar Modal** opens (Sep 29, slots 10:30 AM, 11:15 AM, 4:00 PM)
- Explain: "Demo calendar — in prod connects to your appointment system"
- Click Mark Sent or Simulate Send Due

## Step 6: Human Handoff + Notification (1 min)
- Conversations → select new lead
- Click **Assign to Staff** → select Anjali Patil → add note "Prefers Hindi, callback after 6pm"
- Confirm → lead assigned, follow-ups → stopped, **new notification**: "Assigned: Rahul → Anjali"
- Bell badge updates again

## Step 7: Analytics v2 (1 min)
- **Analytics** → SVG line chart with dots, not just bars
- Status breakdown with animated bars
- Channel breakdown with icons: Website (dark), WhatsApp (green), Phone
- Insight box mentions Hindi + WhatsApp 25%

## Closing (30s)
> "Every enquiry gets an immediate response — in English or Hindi. Every qualified lead is captured from Website or WhatsApp. Every follow-up is tracked. Your team knows what needs attention via notifications. And booking is one click with calendar."

Show Settings → v2 New Features list.

## Checklist
- [ ] Start tour first (2 min)
- [ ] Toggle Hindi in chat
- [ ] Show bell notification after lead capture
- [ ] Filter Conversations → WhatsApp to show green bubbles
- [ ] Click preferred date → calendar modal
- [ ] Assign to staff → show second notification
