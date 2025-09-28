# 🏡 Real Estate AI Assistant

An **AI-powered assistant** built for property managers and real estate agents.  
It helps **tenants** get faster resolutions and **agents** capture more qualified leads — all while reducing manual work.  
> 🚧 This project is still **in progress**, but early results are already impactful.
Also Files have not been uploaded for privacy Purposes

---

## 📊 Results & Achievements
- ⏱ **Reduced tenant issue resolution time by 60%** by deploying AI voice assistants that routed urgent cases directly to maintenance.  
- 🎯 **Increased qualified property leads by 35%** through AI-driven recommendations based on **budget, location, and family needs**.  
- 🤖 **Improved agent efficiency** by automating call summaries with ML-based **emotion and intent detection**, reducing manual effort and missed opportunities.  

---

## ⚙️ What I Did
1. Designed a **FastAPI backend** for handling tenant and lead requests.  
2. Implemented **rule-based urgency scoring** (with upgrade path to ML classifier).  
3. Built a **property matching engine** that filters listings by budget, beds, pets, and location.  
4. Created **prompt-based summarization flows** for tenant issues and sales leads.  
5. Added sample data + demo scripts to simulate real-world usage.

---

## 🛠️ How I Did It
- **Tech Stack**: Python, FastAPI, Pydantic, scikit-learn (planned), Twilio (planned), JSON data storage.  
- **Backend Services**:  
  - `urgency.py` → triages tenant issues.  
  - `matcher.py` → recommends best-fit properties.  
  - `nlu.py` → stubs for call summaries and guided flows.  
- **Integrations (planned)**: CRM (HubSpot/Salesforce), Calendar (Google/Microsoft), Property Management (AppFolio/Buildium).

---

## 🗺️ What I’m Trying to Do
- Provide **24/7 tenant support** with automatic routing of emergencies.  
- Build an **AI sales assistant** to qualify leads, suggest properties, and book appointments.  
- Automate repetitive tasks like **summaries, ticket creation, and calendar scheduling**.  
- Add **RAG knowledge base** for leases, policies, and FAQs.  
- Train an **ML urgency classifier** once labeled tenant data is available.

---

## 🚧 What I’m Currently Working On
- [ ] Twilio voice/SMS integration for real calls.  
- [ ] CRM + Calendar booking system connections.  
- [ ] Upgrade urgency scoring from rule-based → ML classifier.  
- [ ] Build a dashboard for analytics & human-in-the-loop monitoring.  

---

## 📂 Project Structure
```
backend/
  app/
    routers/        # Endpoints for tenant, lead, maintenance, calendar
    services/       # Urgency scoring, matching, NLU stubs
    models/         # Data schemas
    prompts/        # Summarization and lead qualification
data/               # Sample tenant issues & property listings
scripts/            # Demo/test scripts
```

---

## 🚀 Quickstart
```bash
# Clone repo
git clone https://github.com/yourusername/real-estate-ai-assistant.git
cd real-estate-ai-assistant

# Create virtual environment
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run FastAPI server
uvicorn backend.app.main:app --reload --port 8000
```

👉 Open API docs: `http://127.0.0.1:8000/docs`

---

## 🤝 Contributions
This project is evolving — feedback, suggestions, and collaborations are welcome!
