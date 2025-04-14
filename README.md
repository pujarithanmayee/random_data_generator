# random_data_generator

# 🎲 Random Data Generator for Customer Table

This project generates **random dummy data** for a `Customer` table and exports it to CSV format. It then provides a separate script to convert the CSV data into a well-structured **JSON** file. The JSON structure is further refined using Notepad++ for formatting or manual edits.

---

## 📋 Table: Customer

Sample columns generated:
- `CustomerID` (Unique ID)
- `FullName`
- `Email`
- `PhoneNumber`
- `Country`
- `SignupDate`
- `MembershipType` (Free, Silver, Gold, Platinum)

---

## 🔧 Features

- 📄 Generates randomized customer data and saves it as a CSV
- 🔁 Converts the CSV to JSON
- 🧹 Supports structure cleanup/editing via Notepad++ or similar editors
- 🔍 Useful for testing, mock APIs, data science demos, and seeding databases

---

## 📂 Project Structure

random-customer-data-generator/ ├── generate_csv.py # Script to generate CSV with fake customer data ├── convert_to_json.py # Script to convert CSV to JSON ├── customers.csv # Output: Random data in CSV format ├── customers.json # Output: Structured JSON data └── README.md # Project documentation

yaml
Copy
Edit

---

## 🛠️ Requirements

- Python 3.6+
- Libraries:
  - `pandas`
  - `faker`
  - `csv`
  - `json`

Install with:

```bash
pip install pandas faker
🚀 How to Use
1. Generate CSV
bash
Copy
Edit
python generate_csv.py
This will create a customers.csv file with random entries.

2. Convert CSV to JSON
bash
Copy
Edit
python convert_to_json.py
This reads customers.csv and creates customers.json.

3. Refine JSON Structure (Optional)
Open customers.json in Notepad++ and use formatting tools (like JSON viewer plugin) to beautify or modify the structure as needed.

💡 Example Output
CSV (Sample)
css
Copy
Edit
CustomerID,FullName,Email,PhoneNumber,Country,SignupDate,MembershipType
1,John Doe,john.doe@example.com,+1-202-555-0143,USA,2022-01-15,Gold
JSON (After Conversion)
json
Copy
Edit
[
  {
    "CustomerID": 1,
    "FullName": "John Doe",
    "Email": "john.doe@example.com",
    "PhoneNumber": "+1-202-555-0143",
    "Country": "USA",
    "SignupDate": "2022-01-15",
    "MembershipType": "Gold"
  },
  ...
]
📦 Use Cases
Test databases or mock servers

Demo apps and dashboards

Frontend dev requiring sample API data

Machine learning experiments

🙌 Author
Made with 🤖 by Your Name

📄 License
This project is licensed under the MIT License.
Feel free to fork, use, and contribute!

yaml
Copy
Edit

---

Let me know if you want me to include the actual Python scripts (`generate_csv.py` and `convert_to_json.py`) as well!






