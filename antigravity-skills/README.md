# Antigravity & Agent Skills

This folder contains curated skills, rules, and component recipes for AI coding agents (such as Google Antigravity, Cursor, and Claude Code).

## Contents

### 1. Skills (`skills/`)
* **`streamlit-design-system/`**:
  - Comprehensive UI/UX design standards to eliminate the stereotypical "AI-generated" look.
  - Dark slate tokens, master-detail dual-pane architectures, and action toolbars.
  - Production recipes in `examples/recipes.py`.
* **`streamlit-modern-ui/`**:
  - API cheatsheets and pairing standards for combining `streamlit-antd-components` (`sac`) and `streamlit-shadcn-ui` (`ui`).

### 2. Rules (`rules/`)
* **`streamlit-ui-standards.md`**:
  - Auto-enforcing rule file for agents to adhere to clean SaaS design principles when writing Streamlit code.

---

## How to Install in Any Project

### Method A: Global Installation (All Projects on your Machine)
Copy these to your global Antigravity config directory:
```powershell
# Copy skills
Copy-Item -Recurse skills/* "$HOME\.gemini\config\skills\"

# Copy rules
Copy-Item -Recurse rules/* "$HOME\.gemini\config\rules\"
```

### Method B: Single Project Installation
Copy this folder into your project's `.agents/` folder:
```powershell
Copy-Item -Recurse skills <YourProject>\.agents\skills
Copy-Item -Recurse rules <YourProject>\.agents\rules
```

### Required Python Libraries
To use these components in your Streamlit project:
```bash
pip install streamlit-shadcn-ui streamlit-antd-components
```
