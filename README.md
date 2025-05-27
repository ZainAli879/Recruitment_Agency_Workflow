# 📁 Recruitment Agency Workflow (LangGraph)

Welcome!  
This project is an **automated recruitment workflow** designed to streamline how job applications are processed and routed using **Large Language Models (LLMs)** and **graph-based logic**.

---

## 🚀 What Does This Do?

This workflow automatically processes job applications by:

- ✅ **Categorizing candidates** as:
  - Entry-level
  - Mid-level
  - Senior-level

- ✅ **Evaluating** if their skills match the job requirements.

- ✅ **Making decisions based on the evaluation**:
  - ✔️ If the candidate is a **good fit**, schedules an **HR interview**.
  - 📤 If the candidate is **senior** but doesn’t fully match, escalates to a **recruiter**.
  - ❌ If the candidate is **entry or mid-level** and doesn’t match, sends a **rejection**.

All handled programmatically using **LangGraph** — enabling **clear**, **modular**, and **dynamic** workflows.

---

## 💡 Why Use This?

Recruitment often involves:
- Repetitive tasks
- Complex decision-making  

This tool **automates** those tasks, **saves time**, and ensures **fair & consistent** handling of applications.

**Graph-based logic** also allows easy visualization and flexibility to extend the system.

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ZainAli879/Recruitment_Agency_Workflow.git
```

### 2. Set Up Your Environment

Create and activate a virtual environment:

**Linux/macOS:**
```bash
python -m venv .venv
source .venv/bin/activate
```

**Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Set Your API Key

```bash
export OPENAI_API_KEY=your_api_key_here
```

---

## ✏️ Customize Inputs

Update `Recruitment_Agency_Workflow.ipynb` with your:
- Job descriptions
- Candidate applications

---


---

## 📦 Project Structure

| File            | Description                                     |
|-----------------|-------------------------------------------------|
| `Recruitment_Agency_Workflow.ipynb`      | Main workflow logic using LangGraph             |
| `requirements.txt` | Python dependencies                          |
| `README.md`     | Project instructions and overview (this file)  |

---

## 📄 Example Usage

```python
candidate_application = """
Experienced Python developer with 7 years in backend APIs, Django, and cloud deployment.
Proficient in JavaScript and DevOps.
"""

job_description = """
Looking for a Python developer with experience in Django, REST APIs, and cloud platforms.
"""
```

Running the workflow will:
- Categorize the candidate
- Match skills
- Take appropriate next steps

---

## 🤝 Contributions

Contributions and suggestions are **very welcome**!  
Feel free to open issues or submit pull requests.

---

## 📜 License

Licensed under the **MIT License**.

---

If you have questions or want to discuss improvements, open an issue in the repo.  
**Happy automating!** 🚀
