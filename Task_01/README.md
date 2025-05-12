
# FastAPI Starter Project

This is a basic FastAPI setup using `uv` and `fastapi[standard]`.

## 🔧 Setup Instructions

### 1. Create Virtual Environment
```bash
uv venv
```

### 2. Activate Environment (Manually)
```bash
.venv\Scripts\activate
```

### 3. Install FastAPI
```bash
uv add "fastapi[standard]"
```

### 4. Run FastAPI Application
```bash
fastapi dev main.py
```

## 📁 Project Structure
```
/your-project
│
├── main.py
├── README.md
└── .venv/                # Virtual environment folder
```

## 🚀 Notes
- Make sure you have `uv` installed. You can install it via pip:
  ```bash
  pip install uv
  ```
- `main.py` should contain your FastAPI app instance.

---

Happy coding! ✨