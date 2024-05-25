# 10FastFingers Typing Test Automation

## Overview
This Python script automates the typing test on the [10FastFingers](https://10fastfingers.com/typing-test/english) website using Selenium WebDriver. It is designed to automatically type the words displayed in the test, demonstrating how automation can interact with web elements like input fields and buttons.

## Features
- Automatically navigates to the 10FastFingers typing test page.
- Declines cookie consent for uninterrupted automation.
- Types all the words presented in the first row of the test.

## Prerequisites
- Python installed on your machine (Python 3.x recommended).
- Selenium WebDriver library.
- ChromeDriver compatible with the installed version of Google Chrome.

## Installation
1. **Clone or download this repository**:
   ```bash
   git clone [repository-url]
   ```
2. **Navigate to the directory containing the script**:
   ```bash
   cd [directory-name]
   ```
3. **Install Selenium**:
   ```bash
   pip install selenium
   ```
## Setup
Make sure Google Chrome is installed on your machine.
Download the appropriate version of ChromeDriver from the ChromeDriver website and ensure it is in your system's PATH or specify the path in the script.
## Running the Script
To run the script, simply execute:
   ```bash
   python fastfinger.py
   ```
This will start the automated typing test on 10FastFingers. The script types each word and automatically inserts a space after each to simulate real typing.

## Adjustments and Customization
Cookie Handling: If the site updates its cookie policy or element IDs, you may need to update the script accordingly.
Timing Adjustments: The time.sleep() function is used for delays. Adjust these values based on network speed and response times.
Element Selectors: If the website layout changes, you may need to update the CSS selectors or element IDs used in the script.
## Contributing
Contributions to enhance or expand the functionality of this script are welcome. Please fork the repository, make your changes, and submit a pull request.
