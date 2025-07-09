A Python-based voice-enabled task manager that allows you to add, view, update, and delete tasks using both speech and text interfaces. Ideal for productivity enthusiasts who want hands-free control or prefer a simple CLI-based system.

🚀 Features
🎤 Voice Recognition: Add and manage tasks using your voice via Google Speech Recognition.

📋 Text Interface: Full-featured menu-driven CLI for text-based interaction.

🗃️ SQLite Database: All tasks are saved persistently using SQLite.

📅 Due Dates & Priorities: Assign deadlines and prioritize your tasks.

🔄 Update Task Status: Mark tasks as completed, in progress, or pending.

✅ Jupyter-Compatible: Designed to run inside Jupyter Notebook for quick prototyping and testing.

📦 Requirements
Install dependencies using pip:

bash
Copy
Edit
pip install SpeechRecognition pyttsx3 pyaudio
If pyaudio fails to install on Windows:

bash
Copy
Edit
pip install pipwin
pipwin install pyaudio
📁 File Structure
bash
Copy
Edit
📦Voice-Assisted-Task-Manager
 ┣ 📄 Task_Manager_Notebook.ipynb     # Jupyter Notebook version
 ┣ 📄 task_manager.py                 # (optional) Standalone script version
 ┣ 📄 README.md                       # Project documentation
 ┗ 📦 task_management.db              # SQLite database (auto-generated)
🎮 How to Use
✅ Option 1: In Jupyter Notebook
Open Task_Manager_Notebook.ipynb.

Run all cells in order.

Use the terminal-style menu to interact with tasks.

🗣️ Option 2: Voice Interaction
If using the full Python script version (task_manager.py):

Run the script:

bash
Copy
Edit
python task_manager.py
When prompted, choose voice or manual mode.

Speak commands like:

"Add a task"

"View tasks"

"Delete task 2"

"Update task 3 to completed"

📌 Example Commands
Intent	Example Phrases
Add Task	"Add a new task", "Create task"
View Tasks	"Show my tasks", "Display all tasks"
Delete Task	"Remove task 2", "Delete task number 3"
Update Status	"Update task 1 to in progress"

🧠 Built With
Python 3

SpeechRecognition

Pyttsx3

SQLite3
