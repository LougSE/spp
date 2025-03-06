# Prompt Engineering with Windsurf & spp

Windsurf uses a cascading context system, meaning it relies on previous inputs and generated files to maintain coherence. However, it doesn't automatically reference everything unless explicitly told to do so.

---

## How to Use Documents Effectively in Windsurf

### 1️⃣ Use the README as the Foundation

📌 **Key Point:**
Every request should be anchored to `README.md` so that Windsurf keeps the app's purpose in mind.

✅ **Example Prompt:**
```
"Using the guidelines from README.md, implement the authentication system for [APP_NAME]. Follow the user stories and API documentation."
```

---

### 2️⃣ Explicitly Reference Key Docs

📌 **Key Point:**
Windsurf won't automatically check all docs unless told to. When coding a feature, always mention relevant files to prevent inconsistencies.

✅ **Example Prompt:**
```
"Refer to brand_identity.md to ensure UI consistency. Build the login page using the defined fonts and colors."
```

---

### 3️⃣ Follow the Cascade Order

To avoid mistakes, structure requests to align with your documentation order:

1. `README.md` → Overall vision
2. `brand_identity.md` → UI/UX rules
3. `user_stories.md` → Feature requirements
4. `architecture.md` → System design
5. `database_schema.md` → Data structure
6. `api_documentation.md` → Backend endpoints

✅ **Example:**
```
"Build the signup feature based on user_stories.md, ensuring the database matches database_schema.md and API endpoints conform to api_documentation.md."
```

---

### 4️⃣ Use a Standardized Prompt Format

To maintain coherence, always structure prompts like this:

💬 **Prompt Template:**
```
"Using [DOC_1] and [DOC_2], implement [FEATURE]. Ensure compliance with [DOC_3] and [DOC_4]."
```

✅ **Example:**
```
"Using user_stories.md and api_documentation.md, implement the user profile system. Ensure UI consistency based on brand_identity.md and store data according to database_schema.md."
```


## 🔥 Final Takeaway

- Yes, you should **explicitly reference documents** to keep Windsurf from making random decisions.
- Use **step-by-step cascading prompts** so it builds upon existing work logically.
- Standardize your **request format** to prevent AI from deviating.