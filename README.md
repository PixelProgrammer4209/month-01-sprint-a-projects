# Sprint A: Multi-Source Automation & API Integration Showcase

This repository houses production-ready automation workflows built natively in **n8n**, focusing on API authentication, multi-source data aggregation, and conditional routing logic.

---

## 📂 Submission Folder Structure

Inside the repository, you will create a single folder named `[yourname]-[projectname]` (e.g., `john-resume-analyzer`). Your folder must contain the following standard files:

```text
github-repo-hub/
└── john-resume-analyzer/
    ├── workflow.json
    ├── canvas-architecture.png
    ├── configuration-spec.txt
    └── data-transform.js (Optional)
```

### What Each File is For:

* **`workflow.json` (The Blueprint):** The exported JSON text string of your entire automation canvas. This contains the structural node connections and API mapping schemas. *(Security Check: Delete your live secret API keys or account credentials from your workspace before copying your nodes!)*
  
* **`canvas-architecture.png` (The Visual Map):** A clean, full-resolution screenshot of your active canvas board so reviewers can instantly see your workflow layout, routing paths, and node sequences.
  
* **`configuration-spec.txt` (The Integration Manual):** A brief text file detailing your project mechanics. It must explicitly list the external services connected (e.g., Google Sheets, OpenAI, Telegram), the authentication types used (e.g., API Key, OAuth2), and any specific text prompts given to AI nodes.
  
* **`data-transform.js` or `.py` (Custom Logic - Optional):** If your data aggregation required custom JavaScript or Python snippets inside a native "Code Node" to clean up messy JSON payloads, place that raw script here.

---

## Contributing Guidelines

Follow the steps below to submit your solution for this task.

### 1. Fork the Repository
Click the **Fork** button at the top-right of this repository to create a copy of the repository under your personal GitHub account.

### 2. Clone Your Fork
```bash
git clone https://github.com/<your-username>/month-01-sprint-a-projects.git
cd month-01-sprint-a-projects
```
### 3. Create Your Folder & Add Solution
Create a single folder using the lowercase, hyphenated naming convention and place your solution files inside it.

```bash
mkdir john-resume-analyzer
```

### 4. Commit Your Changes
```bash
git add .
git commit -m "Add submission - John Doe (Project Name)"
```
### 5. Push to Your Fork
```bash
git push origin main
```
### 6. Create a Pull Request
1. Open your fork on GitHub.

2. Click Contribute → Open Pull Request.

3. Submit the pull request to this master repository.

#### Pull Request Title Format
```bash
Submission - Your Name - Project Name
```
Example: ```Submission - John Doe - Resume Analyzer```

### Important Notes
- Create only one folder per project using the [yourname]-[projectname] format.

- Do not modify, move, or delete anyone else's submission folder.

- Ensure your workflow exports are sanitized (no live passwords or secret API keys in the JSON code).

- Test your triggers and node connections completely before creating the Pull Request.

Happy building! 🚀
