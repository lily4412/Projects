# Notepad App using Python Tkinter

A simple notepad application built with Python and Tkinter.

## Getting Started

Follow these steps to set up and run the project on your local machine using Visual Studio Code and Python.

### Step 1: Install Python

1. Download and install Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. During installation, make sure to check the option to add Python to the PATH environment variable.

### Step 2: Install Visual Studio Code

1. Download and install Visual Studio Code from: [https://code.visualstudio.com/](https://code.visualstudio.com/)

### Step 3: Install Python Extension for VS Code

1. Open Visual Studio Code.
2. Open the Extensions view by clicking the square icon on the sidebar or pressing `Ctrl+Shift+X`.
3. Search for "Python".
4. Install the extension developed by Microsoft.

### Step 4: Create a Virtual Environment in VS Code

1. Open the Notepad project folder in Visual Studio Code.
2. Open the Command Palette:
   - On Windows: `Ctrl+Shift+P`
   - On macOS: `Cmd+Shift+P`
3. Type `Python: Create Environment` and select it from the list.
4. You will be prompted with two options:
   - `venv`
   - `Conda`
5. Select the first option: `venv`.
6. Then select the Python version installed on your system.
7. VS Code will create a virtual environment for your project. You will see a `.venv` directory created in the root of the project.

### Step 5: Install Tkinter

Tkinter is usually included with standard Python installations. However, to make sure it is available in your virtual environment, run the following command in the terminal:

```bash
pip install tk
```

### Step 6: Run the Notepad Application

1. Open the terminal in Visual Studio Code (`Terminal > New Terminal`).
2. Run the following command:

```bash
python Notepad.py
```

This will launch the Notepad application with a basic graphical user interface built using Tkinter.

## Project Structure

```
Notepad/
├── .venv/             # Virtual environment (auto-generated)
├── Notepad.py         # Main application file
└── README.md          # Project instructions and description
```

## Notes

- Ensure your virtual environment is activated before running the Python script.
- If `tkinter` is not found, make sure Python is installed correctly and includes the Tkinter module.
