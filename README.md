# 🫀 HeartCare Chatbot

HeartCare Chatbot is a Python-based healthcare assistant designed to provide **basic heart health guidance** through conversational interaction.  
It uses a **rule-based approach** to respond to user queries related to heart health and lifestyle awareness.

⚠️ **Disclaimer:** This project is intended for educational and informational purposes only. It does **not** replace professional medical advice, diagnosis, or treatment.

---

## 📌 Project Overview

The HeartCare Chatbot interacts with users via text or a simple graphical interface.  
It analyzes user input, matches keywords with predefined intents, and returns appropriate responses related to heart health.

This project demonstrates:
- Rule-based chatbot logic
- Basic healthcare-oriented conversational systems
- Python scripting and GUI integration

---

## 🧠 Features

- 💬 Interactive text-based chatbot
- 🪟 Optional GUI interface
- ⚙️ Rule-based intent matching
- 🧾 Easy-to-edit intent dataset (`intents.json`)
- 📊 Includes dataset and data analysis notebook
- 🧩 Beginner-friendly and extendable

---

## 🗂️ Project Structure

| File / Folder | Description |
|---------------|------------|
| `chatbot_py.py` | Main chatbot logic |
| `gui.py` | GUI-based chatbot interface |
| `intents.json` | Intent patterns and responses |
| `heart-disease.csv` | Dataset related to heart disease |
| `training_py.py` | Script related to training logic |
| `Data_Analysis.ipynb` | Data analysis notebook |
| `chat.txt` | Sample chat data |
| Model files (`.pkl`, `.h5`, etc.) | Trained or saved models |
| `LICENSE` | Project license |
| `README.md` | Project documentation |

---

## 🛠️ Requirements

- Python 3.8 or higher
- Required Python libraries:
  - `pickle`
  - `tkinter`
  - other standard Python libraries used in the project

> If you do not have a `requirements.txt` file, install the required libraries manually before running the project.

---

## ▶️ Running the Chatbot

### 🖥️ Command Line Version
Run the chatbot in terminal mode:
```bash
python chatbot_py.py

```

## 🪟 GUI Version

Run the chatbot with graphical interface:

python gui.py


Once launched, interact with the chatbot and ask heart health–related questions.

## 📈 How It Works

The chatbot follows a rule-based workflow:

Reads user input.

Matches input keywords with patterns defined in intents.json.

Selects a predefined response for the matched intent.

Displays the response to the user.

This approach makes the chatbot lightweight, fast, and easy to modify.

## 🛠️ Customizing the Chatbot

You can easily extend the chatbot by adding your own questions and responses.

Steps:

Open intents.json

Add a new intent with:

patterns: possible user inputs

responses: chatbot replies

Save the file and restart the chatbot

Example:
{
  "tag": "diet",
  "patterns": ["best diet for heart health", "what to eat"],
  "responses": ["Eat more fruits and vegetables and avoid high-fat foods."]
}


## 📄 License

This project is licensed under the MIT License.
See the LICENSE file for more information.