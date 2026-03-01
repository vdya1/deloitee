# JSON Data Normalization Project (Python)

This project reads multiple JSON files with different data formats and converts them into a **single unified structure** using Python.  
It is designed to demonstrate file handling, JSON parsing, data transformation, and basic testing concepts.

---

## 📌 Project Overview

The program:
- Reads input data from multiple JSON files
- Converts data from different formats into a **standardized schema**
- Compares the generated output with an expected result
- Uses Python’s built-in libraries only

---

## 📂 Project Structure
deloitte/
│
├── data-1.json # Input JSON file (Format 1)
├── data-2.json # Input JSON file (Format 2)
├── data-result.json # Expected output JSON
├── main.py # Main Python script
└── README.md # Project documentation

---

## ⚙️ Technologies Used

- **Python 3.14**
- Built-in libraries:
  - `json`
  - `unittest`
  - `datetime`

No external dependencies are required.

---

## 🚀 How It Works

1. The program reads JSON input files using UTF-8 encoding.
2. Each input format is processed by a dedicated conversion function.
3. The data is transformed into a unified dictionary structure.
4. The result is validated against the expected output JSON.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repository-name.git
2️⃣ Navigate to the project folder
cd deloitte
3️⃣ Run the Python script
python main.py
🛠️ Key Features

Handles multiple JSON formats

Uses UTF-8 encoding to avoid decoding errors

Clean and modular conversion logic

Easy to extend for additional data formats

🧪 Error Handling

The project explicitly specifies file encoding to prevent Unicode decoding errors on Windows systems:

open("file.json", "r", encoding="utf-8")
📈 Learning Outcomes

Through this project, you can understand:

JSON file handling in Python

Data normalization techniques

Writing clean and readable Python code

Basic debugging and error resolution

Structuring a GitHub-ready project
