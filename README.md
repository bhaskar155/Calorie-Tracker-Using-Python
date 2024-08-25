# Calorie and Nutrient Tracker
## Overview
The Calorie and Nutrient Tracker is a Python application designed to help users manage their daily calorie and nutrient intake. It calculates various nutritional goals based on user inputs and tracks food consumption throughout the day. The application visualizes progress using different types of charts, making it easier to monitor and achieve dietary goals.

## Features
•  BMR Calculation: Computes Basal Metabolic Rate (BMR) using the Harris-Benedict equation based on gender, weight, height, and age.

•  TDEE Calculation: Calculates Total Daily Energy Expenditure (TDEE) based on BMR and activity level.

•  Calorie Goals: Determines calorie goals for maintaining, losing, or bulking weight.

•  Nutrient Goals: Sets goals for protein, fat, and carbohydrate intake.

•  Food Tracking: Allows users to add and track food items consumed throughout the day.

•  Data Visualization: Provides visualizations of nutrient distribution and progress towards goals using pie charts and bar charts.

## Requirements
•  Python 3.x

•  Matplotlib (for plotting)

![image](https://github.com/user-attachments/assets/7ff85b79-1563-4762-97e0-c8c7a9183d36)


# Usage
1. Run the Application: Start the program by running calorie_nutrient_tracker.py in your Python environment.
2. Input User Information:

###### •  Gender: Enter 'male' or 'female'.

###### •  Weight: Enter weight in kilograms.

###### •  Height: Enter height in centimeters.

###### •  Age: Enter age in years.

###### •  Activity Level: Choose from options (sedentary, lightly active, moderately active, very active, super active).

###### •  Goal: Choose from options (maintain weight, lose weight, bulk).


3. Add Food:

###### •  Input details of the food item (name, calories, protein, fat, carbs).

###### •  The application will keep track of the total intake for the day.

4. Visualize Progress:

###### •  View various charts showing the distribution of macronutrients, progress towards goals, and daily calorie intake.

5. Quit:

###### •  Exit the application when finished.

# Code Explanation

###### •  calculate_bmr(gender, weight, height, age): Calculates BMR using the Harris-Benedict equation.

###### •  calculate_tdee(bmr, activity_level): Computes TDEE based on BMR and activity level.

###### •  calculate_fat_goal(tdee, fat_percentage): Determines the daily fat intake goal in grams.

###### •  calculate_carbs_goal(tdee, carbs_percentage): Determines the daily carbohydrate intake goal in grams.

###### •  calculate_calorie_goals(gender, weight, height, age, activity_level, goal): Calculates calorie goals and prints results.

###### •  get_user_input(): Prompts the user for input and validates it.

###### •  Food class: Data class to represent food items.

###### •  Visualization: Uses Matplotlib to create charts displaying nutrient distribution and progress.

















