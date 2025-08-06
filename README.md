# 🏖️ Leave Management Assistant (MCP)

This is a simple AI-powered leave management assistant built using [`mcp`](https://github.com/Explorian-AI/mcp) and `FastMCP`. It allows employees to:

- ✅ Check leave balances
- 📝 Apply for leave
- 📜 View leave history
- 💬 Get personalized greetings

---

## 🚀 Quick Start

### 🧩 Prerequisites

- [uv](https://github.com/astral-sh/uv) as Python package manager
- Python ≥ 3.10
- `mcp` library (ensure your environment supports `Python 3.10+`)

---

### ⚙️ Installation

1. Clone the repository or copy the code into a file named `main.py`.

2. Run the app using:

```bash
uv run mcp install main.py
```

3. Install Dependencies

Use uv to install all required packages from requirements.txt:
```bash
uv pip install -r requirements.txt
```

---

## 📦 Dependencies

1. mcp (≥ 1.0.0) — MCP: Modular Command Platform

2. uv — ultra-fast Python package/dependency manager


---

## 🧪 Development Notes

1. This example uses an in-memory dictionary. You can extend this to use a real database or file-based store.

2. Designed for experimentation and extension using the mcp server framework.

---

## 🧠 How It Works

The app uses an in-memory mock database (employee_leaves) and exposes tools using @mcp.tool() and resources using @mcp.resource() decorators provided by FastMCP.

---

