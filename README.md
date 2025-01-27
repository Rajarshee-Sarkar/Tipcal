# Tip Calculator
<br>
A simple Android app that helps you calculate tips and total amounts based on a given base amount and tip percentage. The app provides an intuitive interface for users to quickly determine the appropriate tip and total for their bill.
<br>
# Features
<br>
Dynamic Tip Percentage Adjustment: Use a seek bar to adjust the tip percentage and instantly see the calculated tip and total.
<br>
Tip Description: Get a descriptive label (e.g., "Poor," "Good," "Amazing") based on the selected tip percentage.
<br>
Real-Time Calculations: The app updates the tip and total amounts as you type the base amount or change the tip percentage.
<br>
Color-Coded Feedback: The tip description changes color dynamically to reflect the quality of the tip.

<br>
# Getting Started
<br>
# Prerequisites
<br>
Android Studio installed on your machine.
<br>
A device or emulator running Android 5.0 (Lollipop) or higher.
<br>
# Installation
<br>
Clone the repository:
<br>
git clone https://github.com/yourusername/tip-calculator.git  
<br>
Open the project in Android Studio.
<br>
Sync the Gradle files.
<br>
Run the app on an emulator or physical device.
<br>
# How to Use
<br>
Enter the base amount in the text field.
Adjust the tip percentage using the seek bar.
View the calculated tip amount and total amount.
Observe the tip description and its color change as you adjust the percentage.
# Code Overview
<br>
MainActivity
<br>
The MainActivity class handles:
<br>
UI initialization and event listeners.
<br>
Real-time updates for tip and total calculations.
<br>
Dynamic tip descriptions and color changes based on the percentage.
<br>
# Key Methods
<br>
computeTipAndTotal(): Calculates and displays the tip and total amounts.
<br>
updateTipDescription(tipPercent: Int): Updates the descriptive label and its color based on the selected tip percentage.
<br>
# Colors Used
<br>
color_worst_tip: Represents the lowest tip quality.
<br>
color_best_tip: Represents the highest tip quality.
<br>
# Dependencies
<br>
AndroidX Libraries
<br>
ArgbEvaluator for color transitions
<br>
# License
<br>
This project is licensed under the MIT License - see the LICENSE file for details.
<br>
# Contact
<br>
For any questions or suggestions, feel free to contact:
<br>
Name: Rajarshee Sarkar
<br>
Email: sarkarrajarshee2003@gmail.com
<br>
GitHub: Rajarshee-Sarkar
