🧮 BMI Calculator – Salesforce LWC App 

<img width="1892" height="877" alt="image" src="https://github.com/user-attachments/assets/dfaffbfb-ebd7-4f37-8717-098286369b04" />



The BMI Calculator App is a Salesforce Lightning Web Component based application that allows users to enter their height and weight and instantly calculate their Body Mass Index (BMI).
It uses LWC for UI and Apex for server-side calculation logic.This project demonstrates how Salesforce can be used to build real-time, interactive health utilities using modern UI and backend logic

🎯 What this app does

User enters:

Height

Weight

Clicks Calculate BMI

System returns:

BMI value

Health category (Underweight, Normal, Overweight, Obese)

⚙️ Technology Used

Lightning Web Components (LWC) – UI and user interaction


Apex – BMI calculation logic

Salesforce Platform – Hosting and execution

🧩 How it works (Architecture)
User → LWC UI → Apex Method → BMI Calculated → Result shown on UI


LWC collects height & weight

Calls Apex using:

@salesforce/apex/BMICalculatorController.calculateBMI


Apex calculates BMI

Result is sent back to LWC and displayed

📂 Key Components
LWC

bmiCalculator

Input fields for height & weight

Calculate button

Result display

Apex

BMICalculatorController

Calculates BMI using:

BMI = weight / (height * height)


Returns BMI value and category

This project shows:

How to connect LWC to Apex

How to pass data from UI to backend

How Salesforce can be used to build real-time applications

Clean separation of UI & business logic


