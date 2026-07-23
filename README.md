# HealthCoach Intelligence



\## Overview



HealthCoach Intelligence is an AI-powered prototype that transforms client–coach conversations into structured, evidence-backed insights. Instead of requiring coaches to read lengthy conversations, the system extracts key information and presents it in a clear dashboard to support faster and more informed coaching decisions.



This prototype was built as part of the GenAI Product Intern assignment.



\---



\## What I Built



The solution consists of:



\- A prototype dashboard built using Lovable.

\- An AI analysis prompt that converts conversations into structured client intelligence.

\- A structured JSON output representing the extracted insights.

\- Hallucination prevention strategies to reduce unsupported conclusions.

\- A human-in-the-loop review process where coaches can approve, edit, or reject AI-generated insights.



\---



\## Workflow



Client–Coach Conversation

↓

AI Analysis Prompt

↓

Structured JSON Output

↓

HealthCoach Intelligence Dashboard

↓

Coach Review (Approve / Edit / Reject)



\---



\## Repository Contents



\- `analysis\_prompt.md` – Prompt used to analyze client–coach conversations.

\- `lovable\_prompt.md` – Prompt used to generate the prototype UI.

\- `schema.json` – Basic JSON schema for the expected output.

\- `sample\_output.json` – Example structured output generated from the sample conversation.

\- `hallucination\_cases.md` – Examples of possible AI failure scenarios and mitigation strategies.



\---



\## Key Assumptions



\- The uploaded conversation contains enough information to generate meaningful insights.

\- Coaches will review all AI-generated outputs before making decisions.

\- The AI should only use information explicitly present in the conversation.

\- Medical diagnoses are outside the scope of the system.



\---



\## What Could Go Wrong



\- Missing or incomplete conversations may lead to missing insights.

\- The AI may incorrectly infer behavioral patterns if evidence is limited.

\- Ambiguous statements could be interpreted incorrectly.

\- Important context outside the conversation will not be available to the AI.



\---



\## Future Improvements



\- Support for multiple conversation formats (PDF, DOCX, email, chat exports).

\- Automatic confidence scoring using model probabilities.

\- Trend analysis across multiple weeks of conversations.

\- Integration with Electronic Health Record (EHR) or coaching platforms.

\- Multi-language conversation support.

\- Retrieval-Augmented Generation (RAG) for improved grounding and reduced hallucinations.



\---



\## Technologies Used



\- Lovable (Prototype UI)

\- ChatGPT (Prompt Engineering \& Structured Output)

\- JSON (Data Representation)

\- Markdown (Documentation)



\---



\## Disclaimer



This project is a prototype created for assessment purposes. AI-generated insights are intended to assist health coaches and should always be reviewed by a qualified human before being used for decision-making.

