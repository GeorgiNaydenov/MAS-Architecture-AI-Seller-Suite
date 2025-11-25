# AI Seller – Multi-Agent Sales Architecture

This repo contains a single, browser-based, presentation-style overview of the **AI Seller** multi-agent architecture for B2B sales automation.

---

## Contents

- **`AI_Seller_Crew_Enhanced.html`**  
  An interactive slide deck (React + Tailwind via CDNs) that explains:

  - Business value & KPIs of AI Seller  
  - Core sales use cases (prospecting, outreach, meetings, negotiation, contracts, pipeline insights)  
  - End-to-end user flows across the sales funnel  
  - Multi-agent (MAS / Crew) system architecture  
  - Agent catalog and responsibilities  
  - Data flow & storage (CRM, vector DB, events, ML models)  
  - RBAC and permission boundaries for agents & humans  
  - Security, compliance, observability & incident handling

## What the Deck Is For

- **Product & Sales:** Understand value, flows, and KPIs.
- **Engineers & Architects:** See the MAS / Crew design, agent roles, and integrations.
- **Security / Compliance / Legal:** Review data handling, RBAC, and controls.
- **Clients / Prospects:** Use as a visual explanation of how AI Seller works end-to-end.

---

## Editing the Deck

- All content is in `AI_Seller_Crew_Enhanced.html`.
- Slides are React components styled with Tailwind.
- You can update:
  - Use cases, flows, and KPIs
  - Architecture diagrams & agent descriptions
  - Security, data, and governance details

Edit the file, then refresh your browser to see the changes.

---

## How to View

### Easiest: Open the HTML File

1. Clone or download this repo.
2. Open `AI_Seller_Crew_Enhanced.html` in a modern browser (Chrome, Edge, Firefox).

If the deck doesn’t render due to local file restrictions, use a simple web server.

### Option: Local Web Server (Python)

```bash
# From the repo root:
python -m http.server 8000

# Then open in your browser:
# http://localhost:8000/AI_Seller_Crew_Enhanced.html
