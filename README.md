# 📦 `collect-project`  
> *A minimal, robust CLI tool to dump your Python project structure + source code into a single, review-friendly text file.*

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)](.)

Perfect for:
- 🧠 **AI-assisted code review** (e.g. upload one file to an LLM for full-context analysis)
- 📤 Sending full project context in emails, tickets, or support chats  
- 🕵️ Auditing or snapshotting codebases before refactoring  
- 📁 Archiving lightweight project state (no ZIP, just plain text)

Zero external dependencies — pure Python 3.7+.

---

## 🚀 Quick Start

```bash
# 1. Save the script (e.g. as `collect_project.py`)
curl -O https://raw.githubusercontent.com/your-username/collect-project/main/collect_project.py

# 2. Run from your project root
python collect_project.py

# → Generates `project_analysis.txt`
