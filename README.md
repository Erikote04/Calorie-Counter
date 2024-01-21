# Calorie Counter

Welcome to the Calorie Counter, a simple tool to help you manage your daily calorie intake. This guide provides an overview of the logic and instructions on how to use the Calorie Counter.

## How to Use

1. **Set Your Daily Calorie Budget:**
   - Enter your daily calorie budget in the "Budget" field.

2. **Enter Meal and Exercise Information:**
   - Fill in the calorie input fields for Breakfast, Lunch, Dinner, Snacks, and Exercise.
   - You can add multiple items to each category by clicking the "Add Entry" button.

3. **Calculate Remaining Calories:**
   - Click the "Calculate Remaining Calories" button to see your remaining calorie budget.

4. **Clear Entries:**
   - Use the "Clear" button to reset all the input fields.

## Entry Dropdown:
   - Select the category (Breakfast, Lunch, Dinner, Snacks, Exercise) before adding an entry.

## Output:
   - The calculated remaining calories will be displayed in the output section.

## Script.js Overview

The logic behind the Calorie Counter is implemented in the `script.js` file. Key functionalities include:

- **Input Validation:**
  - The script ensures that the input values are valid and alerts the user if an invalid input is detected.

- **Adding Entries:**
  - Clicking the "Add Entry" button dynamically adds input fields for the selected meal or exercise category.

- **Calculating Calories:**
  - The "Calculate Remaining Calories" button triggers the calculation of remaining calories based on the budget, consumed calories, and exercise calories.

- **Output Display:**
  - The calculated remaining calories, budgeted calories, consumed calories, and burned calories are displayed in the output section.

- **Clearing Entries:**
  - Clicking the "Clear" button resets all input fields and hides the output section.

Feel free to explore and modify the script to customize the Calorie Counter or add new features.

## Getting Started

1. Clone the repository:
   `git clone https://github.com/Erikote04/Calorie-Counter.git`
2. Open index.html in your preferred web browser.
3. Start tracking your daily calories with the Calorie Counter!
