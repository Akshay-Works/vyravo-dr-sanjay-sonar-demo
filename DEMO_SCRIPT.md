# Vyravo AI — Sales Demo Script
**Client:** Dr. Sanjay Sonar Laparoscopy and Scopy Center  
**Type:** Interactive Frontend Prototype (No real integrations)  
**Duration:** 5-10 minutes

## Opening (30s)
> "This is a live demo environment showing how Vyravo AI would handle patient enquiries for your center. Everything you see is demo data — not connected to your hospital systems, WhatsApp, or medical records."

Point to top bar: "Vyravo AI Demo • DEMO ENVIRONMENT"

## Step 1: Patient Enquiry (1 min)
- Click **"Run Live Demo"** (top right) or **"Open Patient Chat"**
- Patient chat widget opens bottom-right (mobile-friendly)
- Show example enquiry: *"Hello, I would like to know about consultation for laparoscopic surgery."*
- Click Send

## Step 2: AI Instant Response (1 min)
- Highlight: AI replies in <2s, professional, concise
- Does NOT give medical diagnosis
- Collects: name, phone, preferred date/time
- Show emergency escalation: type "chest pain" → AI shows emergency notice, not diagnosis
- Walk through:
  - Name → Phone → Date → Email (optional) → Confirmation

## Step 3: Lead Capture (30s)
- After chat completes, toast: "New lead captured"
- Navigate to **Overview** → Recent Enquiries shows new lead at top
- Navigate to **Patient Enquiries** → Card view with status = New Enquiry, source, timestamp
- Open lead drawer → Show captured fields: name, phone, email, enquiry type, preferred date, source, timestamp, conversation transcript

## Step 4: Follow-up Automation (2 min)
- Go to **Follow-ups** tab
- Explain timeline:
  - 0h: Immediate acknowledgement (sent)
  - 24h: "Hi [Name], just following up..." (scheduled)
  - 3d: Second nudge (scheduled)
- Show visual status: sent / scheduled / stopped
- Click "Mark Sent" or "Simulate Send Due" to demo automation
- Emphasize: "No enquiry goes cold — system nudges until staff takes over"

## Step 5: Human Handoff (1 min)
- In **Conversations** → select new lead
- Show follow-up timeline inside conversation
- Click **"Assign to Staff"**
- Select staff (e.g., Anjali Patil - Front Desk), add internal note: "Patient prefers Hindi, callback after 6pm"
- Confirm: "Assign & Stop Automation"
- Result:
  - Lead marked assigned
  - Assigned staff shown
  - Automated follow-ups change to "stopped"
  - Internal note added
  - Conversation shows handoff marker

## Step 6: Dashboard & Analytics (1.5 min)
- **Overview**: Attention Needed (new + follow-up due), positioning card
- **Leads**: Full CRM table, editable status dropdown, search, export CSV (demo)
- **Analytics**:
  - Total enquiries, response rate 100%, follow-ups completed, conversion rate
  - Last 7 days chart (synthetic)
  - Status breakdown
  - Source breakdown
  - Insight box: "2 new enquiries in last hour..."

## Closing (30s)
Reiterate positioning:
> "Every enquiry gets an immediate response. Every qualified lead is captured. Every follow-up is tracked. Your team knows what needs attention."

Show **Settings** tab:
- Clearly states: Not connected to hospital systems, WhatsApp, CRM, medical records
- Staff (demo)
- Channels (mocked)
- Safety note: No medical diagnosis

## Objection Handling
- **"Is this connected to our system?"** → No, this is a demo prototype. Real implementation would connect via secure APIs after approval.
- **"Does AI give medical advice?"** → No. Demo explicitly blocks diagnosis, shows escalation for emergencies.
- **"What about WhatsApp?"** → Mocked in demo, can be integrated as Phase 2.
- **"Pricing?"** → Not shown in demo per instructions — to be discussed separately.

## Technical Notes for Engineer
- Single file: index.html (Tailwind CDN)
- All data in-memory (LEADS array)
- No backend, no real integrations
- Architecture clean for future API wiring
- Responsive: desktop admin + mobile patient chat
- Demo reset via Settings → Reset Demo Data

## Checklist Before Meeting
- [ ] Open demo on laptop + mobile
- [ ] Test Run Live Demo flow end-to-end
- [ ] Clear browser cache if needed
- [ ] Have chat widget open ready
- [ ] Keep this script handy
