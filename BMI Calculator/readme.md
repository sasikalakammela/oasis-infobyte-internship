# BMI Calculator (Python CLI)
## Overview
The BMI Calculator is a simple command-line Python application that calculates Body Mass Index (BMI) based on user input. It helps users understand their health category using standard BMI ranges.
This project is ideal for beginners to practice Python fundamentals such as user input, conditional statements, and error handling.

## Features
* Accepts user input for:
* Weight (in kilograms)
* Height (in meters)
* Calculates BMI using the standard formula
* Classifies BMI into categories:
  * Underweight
  * Normal weight
  * Overweight
  * Obese
* Handles invalid or non-numeric inputs
* Provides clear output to the user

## Technologies Used
* Python (Core Programming)

## Installation
1. Clone the repository:
```id="clone123"
git clone https://github.com/sasikalakammela/oasis-infobyte-internship/tree/main
```
2. Navigate to the project folder:
```id="nav123"
cd bmi-calculator
```

## Usage
Run the program:
```id="run123"
python bmi_cli.py
```
Enter your weight and height when prompted.

## BMI Formula
BMI = weight (kg) / (height (m))²
Example:
* Weight = 50 kg
* Height = 1.5 m
* BMI = 22.22 (Normal weight)

## Project Structure

```id="struct123"
bmi-calculator/
│── bmi_cli.py
│── README.md
```

## Key Concepts Demonstrated
* User input handling
* Conditional statements (if-else)
* Functions in Python
* Exception handling (try-except)

## Future Improvements

* Add GUI interface using Tkinter
* Store user data for tracking
* Add unit conversion (cm to meters automatically)

## Author

* Name: Kammela Sasikala
* Role: Computer Science (AI & ML) Student

## License
This project is open-source and available under the MIT License.
