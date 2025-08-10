# Regex Data Extraction Project

## 📌 Overview
This project demonstrates how to use **Python Regular Expressions (regex)** to extract structured data from unstructured text.  
It processes a text containing personal and billing information, then extracts:
- Phone numbers
- Email addresses
- Birthdates
- Insurance IDs
- Bill amounts

The extracted data is then stored in a **pandas DataFrame** for easy viewing and further processing.

---

## 🛠 Technologies Used
- **Python 3**
- **re** (Regular Expressions)
- **pandas** (Data handling)

---

## 📂 Project Structure
```
regex.ipynb       # Jupyter Notebook containing the code and outputs
README.md         # Project documentation
requirements.txt  # Required Python packages
```

---

## 🚀 How to Run

1. **Clone the repository** or download the files.
   ```bash
   git clone <your-repo-link>
   cd <your-project-folder>
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook regex.ipynb
   ```

---

## 📊 Example Output
Given the following text:
```
Alice Smith recently visited our clinic. Her phone number is 7321119999, 
and you can reach her at alice.smith@example.com for any follow-up information. 
She was born on 1990-05-15. Her insurance ID is INS-123456. 
The bill amount for her recent appointment is 120$.
```
The output will be:
| Phone Number | Email                   | Birthdate  | Insurance ID | Bill Amount |
|--------------|------------------------|------------|--------------|-------------|
| 7321119999   | alice.smith@example.com | 1990-05-15 | INS-123456   | 120         |

---

## 📜 License
This project is for educational purposes. You are free to modify and use it for learning.
