# CPL AI Evaluation Platform  
### Cloud-Deployed Conversational Agents for Credit for Prior Learning Assessment

This project is a cloud-deployed AI platform designed to support **Credit for Prior Learning (CPL)** evaluation through structured conversational interviews, evidence collection, and stakeholder-facing demonstrations.

The system was developed as part of a graduate capstone course and sponsored by faculty involved in CPL application review. Student teams designed and deployed their own conversational AI applications, while the instructor platform provided infrastructure, evaluation, and benchmarking support.

---

## Project Highlights

- Built and deployed multiple AI chatbot web applications on **Azure App Service**
- Integrated **Azure OpenAI** for structured CPL interview conversations
- Used **Azure SQL** for application data, logging, testing, and evaluation
- Supported live demos with real faculty stakeholders
- Built an instructor evaluation dashboard to compare chatbot performance across teams
- Evaluated systems using standardized CPL scenarios and rubric-based scoring

---

## Problem Context

Credit for Prior Learning evaluation requires students to clearly explain prior work, training, certifications, or academic experience in ways that faculty can evaluate.

A major challenge is collecting information that is:

- specific
- evidence-based
- relevant to course outcomes
- consistent across students
- safe from unsupported approval claims

This project explores how conversational AI can support the early intake and evidence-gathering stage of CPL review.

---

## System Architecture

At a high level, the project includes:

- Student-facing chatbot web applications
- Azure OpenAI model integration
- Azure SQL databases for each team
- GitHub Actions deployment pipelines
- Instructor control/evaluation platform
- Standardized test scenarios and rubric-based scoring

---

## Live Team Applications

The following deployed applications represent the completed student team prototypes:

- **Team 1 – Creative Catalysts:**  
  https://cpl-team1-app-bwffb8cpf4fzf6ef.eastus-01.azurewebsites.net/

- **Team 2 – LuckyDucky:**  
  https://cpl-team2-app-faeda5cvfjc3e4d8.eastus-01.azurewebsites.net/

- **Team 3:**  
  https://cpl-team3-app-dqecavgmhvecavb6.eastus-01.azurewebsites.net/

- **Team 4:**  
  https://cpl-team4-app-bjakewhwdrbwc8fa.eastus-01.azurewebsites.net/

- **Team 5:**  
  https://cpl-team5-app-gjdpfpebfxcnf5cp.eastus-01.azurewebsites.net/

Note: Applications may have usage limits enabled to manage cloud/API costs.

---

## Instructor Evaluation Platform

The instructor platform supports:

- Testing all team chatbots from one interface
- Running standardized CPL test scenarios
- Benchmarking all teams across multiple scenarios
- Capturing latency, response quality, and rubric scores
- Exporting benchmark results
- Logging evaluation results to Azure SQL

Evaluation dimensions included:

- Interview quality
- Specificity
- Professional tone
- Policy safety
- Evidence focus
- CPL alignment

---

## Technologies Used

- Python
- Flask
- Azure App Service
- Azure OpenAI
- Azure SQL Database
- GitHub Actions
- HTML/CSS/JavaScript
- pyodbc
- Gunicorn

---

## Skills Demonstrated

This project demonstrates experience with:

- Applied generative AI system design
- Prompt engineering and conversational workflow design
- Cloud deployment and DevOps with Azure + GitHub Actions
- Database-backed web application development
- AI evaluation and benchmarking
- Stakeholder-centered product prototyping
- Responsible AI design for education workflows

---

## Status

The project reached a working prototype stage and was presented to CPL faculty stakeholders. Faculty feedback will inform future development toward a more complete CPL intake and decision-support tool.

---

## Original Infrastructure Release

Stable infrastructure release: `v1.0-stable-infra`

This release provided the baseline Azure deployment structure used by student teams.
