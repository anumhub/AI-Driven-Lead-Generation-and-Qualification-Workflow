# AI-Driven-Lead-Generation-and-Qualification-Workflow(Make.com)
This project demonstrates an AI-powered lead generation and qualification workflow built using Make.com, OpenAI, and Google Sheets. The solution automates lead scoring, routing, deduplication, and follow-up actions while ensuring structured AI outputs and reliable workflow execution.

The project focuses on applying QA principles to AI-driven automation, including validation, error handling, and monitoring of non-deterministic AI behavior.


## Key Features
- AI-based lead intent analysis with structured JSON output
- Automated lead scoring and classification (High / Medium / Low intent)
- Conditional routing for sales follow-up or nurture pipeline
- Duplicate lead detection to avoid repeated processing
- Accurate timestamp handling across UTC and PST
- Google Sheets used as a lightweight CRM
- Email notifications and follow-up automation

## Tech Stack
- **Automation Platform:** Make.com  
- **AI Model:** OpenAI (JSON-based prompt outputs)  
- **Data Storage:** Google Sheets  
- **Notifications:** Gmail  
- **Documentation & Testing:** Test scenarios, workflows, and execution logs  

---

## Repository Structure
- Lead Generation-Executive-Summary → Project overview and objectives
- Prompt → AI prompt and JSON structure
- Scenarios cover for Demo + Test Data for Requiement field→ validation scenarios and test data for requirement field
- Lead Generation- Automation Workflow Overview → Make.com workflow documentation
- Lead Generation-Demo-video → End-to-end demo recording


## Testing & QA Approach
- Validated AI outputs against strict JSON schema
- Tested happy paths, edge cases, and failure scenarios
- Verified routing logic and fallback handling
- Ensured deduplication across multiple workflow runs
- Checked timestamp accuracy and execution consistency

## Challenges Faced
- Ensuring consistent AI scoring and structured outputs
- Preventing duplicate leads across repeated runs
- Debugging conditional routing and missing logs
- Managing time zone differences in timestamps

## Future Improvements
- Add weighted scoring based on behavioral signals
- Implement feedback loops to improve AI accuracy
- Enhance deduplication using fuzzy matching
- Replace Google Sheets with a scalable database
- Add automated monitoring and failure alerts


## Demo
A complete demo video is included in this repository showing:
- Lead ingestion
- AI scoring and routing
- Sheet updates
- Email notifications
