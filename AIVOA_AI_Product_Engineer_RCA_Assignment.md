[**AIVOA.AI**](http://AIVOA.AI)

# **AI Product Engineer Challenge**

**Build an AI-Powered Root Cause Analysis (RCA) Module**

| GOAL  •  Build a working AI-powered Root Cause Analysis workflow for a pharmaceutical manufacturer producing Active Pharmaceutical Ingredients (API). |
| :---- |

# **1\. What You Need to Build**

Research how pharmaceutical manufacturers investigate quality issues during API manufacturing. Based on your research, design and build a working AI-powered RCA module that helps quality professionals investigate incidents, analyze available evidence, identify potential root causes, and **recommend corrective and preventive actions (CAPA).**

**Understand the End-to-End Quality Workflow**

Before developing the product, research how an **API pharmaceutical manufacturer** handles a quality incident through the following workflow:

**Deviation Identification → Root Cause Analysis (RCA) → Corrective and Preventive Actions (CAPA)**

Understand how a deviation is recorded and investigated, how its root cause is identified using supporting evidence, and how appropriate corrective and preventive actions are defined and tracked.

Design your module to demonstrate how AI can assist quality professionals throughout this workflow, from deviation information intake to root cause analysis and CAPA recommendations, while allowing users to review and edit AI-generated information.

Research the workflow independently and make sensible product and design decisions. No UI template is provided.

.

# **2\. Reference UI**

No reference UI screenshot is provided. You may use the reference demo video below only to understand the AI workflow and interaction pattern.

**IMPORTANT  •**  The reference demo video is for the Customer Complaint module. DO NOT build the Customer Complaint, Deviation, or Change Control module. Use the video only to understand the AI workflow and interaction pattern, then build the equivalent AI-powered workflow for Root Cause Analysis.

# **3\. Reference Demo Video**

**Video:** AIVOA.AI – Customer Complaint Module Demo

https\://drive.google.com/file/d/1av2lzDPx8YMSzTrIz7w51HTRWBz3\_5Nj/view?usp=sharing

# **4\. AI Requirements**

Your module should demonstrate a practical AI-assisted workflow, including:

* Accept an incident / investigation document (PDF), pasted text, or email.  
* Use AI to extract relevant information and populate the RCA form.  
* Support an investigation approach such as 5 Whys or fishbone analysis.  
* Identify potential root causes and contributing factors based on the information provided.  
* Highlight missing evidence or information that may be needed for further investigation.  
* Provide CAPA recommendations with a short explanation, where applicable.  
* Allow the user to review and edit AI-generated information before saving the investigation.

**Important:** Do not manually fill the form as the primary workflow. Use the AI panel to extract information and populate the form, following the interaction pattern demonstrated in the reference video. AI-generated causes must be treated as suggestions unless supported by evidence and confirmed by a qualified person.

# **5\. Tech Stack (Mandatory)**

**Frontend:** React \+ Redux

**Backend:** Python \+ FastAPI

**AI:** LangGraph \+ Groq

**Database:** PostgreSQL / MySQL

Groq: gemma2-9b-it, llama-3.3-70b-versatile, or any other reliable supported model. ([https\://console.groq.com/keys](https://console.groq.com/keys))

# **6\. Demo & Submission**

Submit two separate video recordings:

**Video 1: Product Demonstration (5–8 minutes)**

Demonstrate the working application and focus on the user experience and AI-powered form-filling tools.

* Show the document / text / email input.  
* Demonstrate AI processing and information extraction.  
* Show the extracted information automatically populating the RCA form.  
* Demonstrate the AI-assisted investigation, root cause analysis, and CAPA recommendations.  
* Show the user reviewing and editing AI-generated information, then saving the investigation.

**Video 2: Code Explanation (5–10 minutes)**

Explain the implementation and walk through the complete end-to-end workflow, including:

* Frontend structure and form-filling interactions.  
* API endpoints and backend processing.  
* Document / text extraction and AI tool integration.  
* LangGraph workflow and LLM integration.  
* How AI-generated information populates the RCA form and produces investigation recommendations.  
* Database integration and how the investigation is saved.

**Important:** Do not upload the project, source code, demo videos, assignment files, screenshots, sample documents, or any other assignment materials to GitHub or any public repository.

**Deliverables**

* Working application.  
* Video 1: Product demonstration (5–8 minutes).  
* Video 2: Technical walkthrough (5–10 minutes).

**Submission Form: [https\://forms.gle/4XzMgThdQ7KnG2HU7](https://forms.gle/4XzMgThdQ7KnG2HU7)**

**Deadline:** 48 hours

# **7\. What We Look For**

Take ownership. Research what you need, make sensible product decisions, and build a complete working flow without waiting for every detail to be specified.

**AI coding tools are allowed and encouraged**. You should understand what you build and be able to explain or modify it during the interview.