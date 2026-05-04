# Test Automation Project – Singlish Translator

## Setup Instructions

1. Install Python (version 3.10 or above)

2. Install dependencies:
pip install -r requirements.txt

OR manually:
pip install playwright openpyxl

3. Install Playwright browsers:
playwright install

## Run the Automation Script

python test_automation.py --excel "IT12345678_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

## Optional Parameters

--wait-ms 5000
--type-delay-ms 80
--slow-mo-ms 200
--save-every 1
--keep-open

Example:
python test_automation.py --excel "IT12345678_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --keep-open

## Project Description

This project automates testing of a Singlish to Sinhala translator using Playwright. It reads test cases from an Excel file, inputs them into the web application, and compares actual vs expected outputs.