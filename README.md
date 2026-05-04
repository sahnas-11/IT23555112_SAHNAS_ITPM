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