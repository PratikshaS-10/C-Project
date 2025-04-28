# 🧠 Mental Health Checker (C Project)

This is a console-based C application that helps users assess their mental health based on a questionnaire.  
It calculates a score, gives feedback, saves data securely, and even offers fun games and mystery surprises to improve well-being.

---

## 🧾 Features

- ✅ Mental health self-assessment with 15 questions
- 📊 Score calculation and personalized feedback
- 💾 Binary file handling to save & retrieve scores
- 📈 Score analysis: average, best, worst, and variance
- 🧠 Graph plotting using Python
- 🎮 Mini-games: Number Guessing, Stone-Paper-Scissors
- 🎁 Mystery box: jokes, pranks, and positive thoughts
- 🔗 Helpful mental health resources

---

## 💻 How to Run

1. **Clone this repo** or download the files
2. Compile the C code:
   ```bash
   gcc mental_health_checker.c -o mental_health
3. Run the code:
   ./mental_health
   If you're on Windows and using something like MinGW or TDM-GCC, the command will be:
   mental_health.exe

🧠 If Score Plotting Is Enabled
The program uses a Python script named generate_chart.py to plot user scores. To enable this:

1. Make sure Python is installed:
python --version
2. Install matplotlib (if not installed):
pip install matplotlib
3. Ensure the script generate_chart.py is in the same folder.
The C program calls this script using system("python generate_chart.py");
