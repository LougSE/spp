# SPP (Super Power Prompts) Workflow for [APP_NAME]

Before you run:
This workflow is supposed to be run step by step so it can be supervised and modified as needed.

---

## Step 1: Define the Project

📌 **Prompt:**
"Generate a README.md for an application named [APP_NAME]. It should include a brief overview, target audience, core features, and the problem it solves."

📌 **Output:** `README.md`

---

## Step 2: Establish Brand Identity

📌 **Prompt:**
"Using the project details from README.md, create a brand identity file for [APP_NAME] including primary and secondary colors (hex codes), typography (Google Fonts), and UI style guidelines. Ensure consistency across all UI elements."

📌 **Input:** `README.md`
📌 **Output:** `brand_identity.md`

---

## Step 3: Define User Stories

📌 **Prompt:**
"Based on README.md, generate user stories for [APP_NAME]. Each story should follow the format: 'As a [USER], I want to [ACTION], so that I can [BENEFIT]'. Consider different user roles."

📌 **Input:** `README.md`
📌 **Output:** `user_stories.md`

---

## Step 4: Plan the System Architecture

📌 **Prompt:**
"Using user_stories.md, generate a high-level system architecture for [APP_NAME], including frontend, backend, database, and external services. Ensure modular design for scalability."

📌 **Input:** `user_stories.md`
📌 **Output:** `architecture.md`

---

## Step 5: Define Database Schema

📌 **Prompt:**
"Based on architecture.md and user_stories.md, create an Entity-Relationship Diagram (ERD) for [APP_NAME]. Include necessary tables, primary keys, and relationships."

📌 **Input:** `architecture.md`, `user_stories.md`
📌 **Output:** `database_schema.md`

---

## Step 6: Define API Endpoints

📌 **Prompt:**
"Using user_stories.md and database_schema.md, generate REST API documentation for [APP_NAME]. Include endpoint paths, request/response formats, authentication methods, and error handling."

📌 **Input:** `user_stories.md`, `database_schema.md`
📌 **Output:** `api_documentation.md`

---

## Step 7: Define UI Components

📌 **Prompt:**
"Based on brand_identity.md and user_stories.md, list the UI components needed for [APP_NAME] (e.g., buttons, modals, forms). Ensure they follow the branding guidelines."

📌 **Input:** `brand_identity.md`, `user_stories.md`
📌 **Output:** `ui_components.md`

---

## Step 8: Set Up DevOps & Deployment

📌 **Prompt:**
"Using architecture.md and api_documentation.md, generate a deployment plan for [APP_NAME], including CI/CD pipeline setup, hosting strategy, and scalability recommendations."

📌 **Input:** `architecture.md`, `api_documentation.md`
📌 **Output:** `devops.md`

---

## Optional Steps

### Define Core Features & Priorities

📌 **Prompt:**
"Based on README.md and user needs, define a list of features for [APP_NAME]. Prioritize them into MVP, V1.0, and Future Releases."

📌 **Output:** `features.md`

### Component Breakdown

📌 **Prompt:**
"Based on brand_identity.md and features.md, list UI components needed for [APP_NAME] (e.g., buttons, modals, forms) and their interactions."

📌 **Output:** `ui_components.md`

### Set AI Constraints & API Rules

📌 **Prompt:**
"List AI constraints for [APP_NAME], including coding style, UI structure, and API formatting rules."

📌 **Output:** `docs/ai_constraints.md`

### Track Changes

📌 **Prompt:**
"Log updates for [APP_NAME] in a structured format (feature updates, bug fixes, etc.)."

📌 **Output:** `docs/CHANGELOG.md`

### Competitive Analysis

📌 **Prompt:**
"Analyze competitors of [APP_NAME]. Identify their strengths, weaknesses, and opportunities for differentiation."

📌 **Output:** `competitive_analysis.md`

### AI Constraints & Guardrails

📌 **Prompt:**
"Define AI constraints for [APP_NAME] to ensure consistency in code structure, styling, API calls, and generated components."

📌 **Output:** `ai_constraints.md`

### Versioning & Changelog

📌 **Prompt:**
"Track version changes for [APP_NAME], including new features, bug fixes, and API modifications."

📌 **Output:** `CHANGELOG.md`

---

🔥 **This workflow will make us build apps like a large-scale tech company.**

**Last update: 2025-02-21**
