# Singlish to Sinhala Translation Testing Automation

## Project Overview

This project was completed as part of **Assignment 01** for software testing. The objective was to identify **50 negative test cases** where the **Pixelssuite Chat Translator** fails to correctly convert **Singlish to Sinhala** text.

The project includes:

* Manual creation of 50 failing test cases
* Categorization based on provided Singlish input types
* Automated execution using **Playwright**
* Automatic extraction of actual outputs
* Automatic pass/fail status generation
* Documentation of evidence and rationale

---

## Application Under Test

Website: https://www.pixelssuite.com/chat-translator

Testing Mode Used:

* **Chat Sinhala**

---

## Test Case Requirements

The assignment required:

* 50 negative test cases
* Minimum 2 test cases from each of the 24 input categories
* All test cases must produce incorrect translations
* Test case IDs starting with `Neg_`

Example:

* Neg_0001
* Neg_0002

---

## Project Structure

```bash
test_automation/
│
├── Assignment 1 - Test cases.xlsx
├── test_automation.py
├── requirements.txt
└── README.md
```

---

## Technologies Used

* Python
* Playwright
* OpenPyXL
* Excel

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/your-repository-name.git
```

Move into the project directory:

```bash
cd test_automation
```

Install dependencies:

```bash
pip install -U pip
pip install playwright openpyxl
```

Install Playwright browsers:

```bash
playwright install
```

---

## Running the Automation Script

Run the following command:

```bash
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## Output

After execution:

* Column E → Actual Output generated automatically
* Column F → Pass/Fail Status generated automatically

Manual completion:

* Column G → Input Type
* Column H → Evidence/Rationale

---

## Expected Outcome

The script automatically tests all 50 negative scenarios and identifies translation failures in the system.

---

## Author

**Name: Sahnas Thufail
**Registration Number: IT23555112

---
# IT23555112_SAHNAS_ITPM
