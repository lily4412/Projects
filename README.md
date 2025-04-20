
## 📝 Notepad App using Python Tkinter

A simple notepad application built with Python and Tkinter.

---

## ✅ Getting Started

Follow these steps to set up and run the project on your local machine.

### 🔧 Step 1: Install Python

1. Download and install Python from the official site: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. During installation, check ✅ “Add Python to PATH”.

### 💻 Step 2: Install Visual Studio Code (VS Code)

1. Download and install VS Code from: [https://code.visualstudio.com/](https://code.visualstudio.com/)

### 🔌 Step 3: Install Python Extension in VS Code

1. Open VS Code.
2. Go to **Extensions** (`Ctrl+Shift+X` or click the square icon on the sidebar).
3. Search for **Python**.
4. Install the one published by **Microsoft**.

### 📦 Step 4: Set Up a Virtual Environment (Optional but Recommended)

1. Open **Terminal** in VS Code (`Terminal > New Terminal`).
2. Navigate to the project directory (where `Notepad.py` is located).
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:

   - **On Windows:**
     ```bash
     .\venv\Scripts\activate
     ```
   - **On macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

### 🛠️ Step 5: Install Tkinter

Tkinter usually comes pre-installed with Python. But to ensure it's available in your virtual environment, run:

```bash
pip install tk
```

### ✅ Step 6: Run the Project

1. Open `Notepad.py` in VS Code.
2. Click **Run > Run Without Debugging** or press `Ctrl+F5`.

You should see a basic GUI Notepad open using Tkinter.

---

## 📂 Project Files

- `Notepad.py` – Main Python file containing the Notepad GUI code.
- `README.md` – Setup instructions (this file).

---

## ✨ Features

- Open, save, and edit text files
- Simple and clean GUI using Tkinter

---

## 💡 Tip

If you're having issues running the file, double-check:
- Python is correctly installed and added to PATH.
- You're in the right directory in the terminal.
- Your virtual environment is activated.
