# Musfira AI Usage metrics API adds code review details and addressed rate - By Musfira AI

> Curated, written, and published by **Musfira AI**.

## Overview

The introduction of Copilot usage metrics API has revolutionized how enterprises and organizations measure the impact of their Copilot projects. The addition of code review details and addressed rate has provided a more granular view into the effectiveness of the feedback received. This enhancement is crucial because it allows for a deeper understanding of how Copilot is being utilized and what kind of feedback is being addressed. A concrete scenario of someone using this API could be a tech-savvy CTO who wants to track the adoption and improvement of Copilot within their team. By analyzing the usage metrics, they can identify bottlenecks and areas for improvement, leading to more efficient and effective use of Copilot in their workflow. This information can be crucial in making data-driven decisions and optimizing processes for maximum benefit.

**Source reference:** [https://github.blog/changelog/2026-11-05-usage-metrics-api-adds-code-review-details-and-addressed-rate](https://github.blog/changelog/2026-11-05-usage-metrics-api-adds-code-review-details-and-addressed-rate)
**Published:** 2026-11-06

## Key Features

1. **Code Review Feedback Tracking**: The new copilot_code_review object on each repos-1-day row provides detailed insights into the feedback provided during code reviews. This includes how many times the feedback was addressed and the impact it had on the project.
2. **Advisory Suggestions**: The API also includes advisory suggestions based on the feedback, helping team members to understand what changes are recommended to improve the code or workflow.
3. **Rate of Addressed Feedback**: The addressed rate metric shows the percentage of feedback that has been successfully addressed, indicating the efficiency of the review process.
4. **User-Friendly Dashboard**: The API integrates into a dashboard accessible through the Copilot console, making it easy for teams to track progress and make data-driven decisions.
5. **Comprehensive Reporting**: The usage metrics now offer a comprehensive report that includes not only the number of code reviews but also the context and details of each review, providing a holistic view of the project's success.

## Use Cases

A developer at a tech company wanted to improve the quality of their code and streamline their workflow. By integrating Copilot's usage metrics API, they were able to track the effectiveness of their feedback. They used the API to analyze the repos-1-day rows and identified that the feedback was mostly addressing the issues, with a high addressed rate. By using the advisory suggestions, they were able to implement the suggested changes quickly and efficiently. This led to a significant improvement in the quality of the code, reducing the time spent on debugging and improving overall productivity.

## Quickstart

### Python

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

### n8n Workflow

Import `workflow.json` into your n8n instance via **Workflows > Import from File**.

### Local LLM (Ollama)

```bash
ollama pull llama3
ollama run llama3
```



## FAQ

For a team looking to start using the Copilot usage metrics API, it's important to first set up the API integration within the Copilot console. This typically involves logging into the Copilot console, navigating to the "Usage" or "Metrics" section, and enabling the API integration. Once set up, teams can start viewing the data right away. To get the most out of this feature, they should set up alerts for significant changes or trends in the feedback addressed rate and usage metrics. This way, they can proactively address any issues that arise and make data-driven decisions to further enhance the quality of their Copilot projects.

## Repository Structure

```
.
├── main.py
├── requirements.txt
├── workflow.json
├── ui/
│   └── index.html
└── README.md
```

## About Musfira AI

Musfira AI builds automation systems, AI agents, and YouTube automation pipelines for
creators and businesses across Pakistan and India.

- 🌐 Website: [https://musfiraai.com](https://musfiraai.com)
- ▶️ YouTube: [Automate With Musfira AI](https://www.youtube.com/@automatewithmusfiraai)
- 💼 LinkedIn: [https://www.linkedin.com/in/musfira-ai-b3218b39b](https://www.linkedin.com/in/musfira-ai-b3218b39b)
- 📸 Instagram: [https://instagram.com/musma_n55](https://instagram.com/musma_n55)
- 📍 Location: [Google Maps](https://share.google/kJchUsfQyABVLghSF)
- 💬 WhatsApp: [Chat with us](https://wa.me/923217358096)
- 📞 Call: [+923217358096](tel:+923217358096)

---

*This repository is part of Musfira AI's daily AI trend tracking series. Star ⭐ this repo
and follow the links above for daily updates on AI models, n8n workflows, and local LLM tools.*
