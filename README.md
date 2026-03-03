# PRD Agents
### Turn Meetings into Execution

Open-source multi-agent system that transforms meeting transcripts into structured execution artifacts:

- Product Requirement Document (PRD)
- Jira execution plan (JSON)
- ROI model
- Structured notes

Built for product teams who want to move from discussion to execution automatically.

---

## What This Is

PRD Agents is a lightweight multi-agent orchestration framework.

It simulates a small product team in code:

- **Orchestrator Agent** – Coordinates the workflow
- **Analyst Agent** – Extracts key insights and requirements
- **Product Agent** – Generates structured PRD and Jira plan
- **Finance Agent** – Builds ROI model and financial reasoning
- **Librarian Agent** – Loads context and supporting materials

Instead of summarizing meetings, it produces execution-ready artifacts.

This is not a chatbot.
It’s a structured execution engine.

---

## How It Works
Transcript → Orchestrator → Agents → Structured Outputs

1. Drop a meeting transcript into `/transcripts`
2. Run the system
3. Receive structured artifacts inside `/out`

---

## Quick Start

### 1. Clone the repository

git clone https://github.com/raduandreibulai/prd-agents
cd prd-agents
### 2. Add a transcript
Place your meeting transcript inside:
/transcripts
Example:
/transcripts/meeting.txt
### 3. Run the system
python run.py
### 4. View outputs
Generated artifacts will appear in:
/out
Depending on configuration, outputs may include:
prd.md
jira_plan.json
roi_model.md
notes.md
Example Output
PRD (Excerpt)
Problem:
Low enrollment rate on APL landing page.

Hypothesis:
Introducing trust markers above the fold will increase Direct-to-MP rate by 8–12%.

Success Metrics:
- Direct-to-MP Rate
- Enrollment Rate
- Marketing Margin
Jira Plan (Excerpt)
{
  "epic": "APL Landing Page Revamp",
  "stories": [
    {
      "title": "Add trust markers above fold",
      "acceptance_criteria": [
        "Trust badges visible on mobile and desktop",
        "A/B test enabled 50/50 split"
      ]
    }
  ]
}
Architecture
The system follows a modular multi-agent orchestration pattern:
- Agents are isolated and specialized
- Orchestrator controls sequencing
- Context pack enables external knowledge injection
- Outputs are deterministic and structured
Designed to be extended with:
- Additional agents
- API layer
- Web UI
- Vector database integration
### Why I Built This
As a Product Manager, I noticed that meetings generate decisions — but rarely structured execution artifacts.
PRD Agents automates the path from messy conversation to execution clarity.
It’s an experiment in operational AI:
What if your product team could be partially encoded?
### Roadmap
- Web UI
- API wrapper
- Docker support
- Plug-in agent architecture
- Configurable output templates

### License
MIT License — use freely, modify, extend.

### Contributing
Pull requests are welcome.
For major changes, please open an issue first to discuss what you’d like to change.

### Author
Built by Radu Bulai
Product x AI Systems

---

# 🔥 Why This Version Works

It:

- Feels like a real system
- Has a clear hook
- Has structured quick start
- Shows example outputs
- Signals credibility
- Signals future expansion
- Positions you as a system builder

---

If you want next, I can:

- Make a shorter “lean hacker” version  
- Make a more technical architect-level version  
- Or help you design a visual diagram to embed at top  

This is already strong enough to stand on its own.
