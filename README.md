DividendCalculator (Android - Java)
A simple and clean Android application that calculates monthly and total dividend returns based on invested fund amount, annual dividend percentage, and number of months.
Includes a dedicated About page, toolbar menu navigation, and GitHub link redirection.

App Features
1. Dividend Calculation

User inputs:
Invested Fund Amount (RM)
Annual Dividend Rate (%)
Months Invested (1–12)

Application performs:
monthlyDividendRate = (annualRate / 100) / 12
monthlyDividend = monthlyDividendRate * investedFund
totalDividend = monthlyDividend * numberOfMonths
Results are formatted to two decimal places using DecimalFormat.

2. Clean UI Design
Material Components TextInputLayout for input fields.
ScrollView layout for smooth display on all devices.
Rounded result display using rounded_background.xml.

3. Toolbar + Menu Navigation
Custom Toolbar integrated in MainActivity.

Options menu:
Home
About
Smooth navigation to AboutActivity via menu item.

4. About Page
Custom toolbar with back/up navigation.

Displays:
App name
Author name
Matric number
Course info
Footer copyright
Clickable GitHub repository link.

Author
Haziq Najib Mokhtar
Matric No: 2023485702
Course: CDCS240 — Mobile Technology and Development

How to Build & Run
Open Android Studio.
Click:
File → New → Import Project
or open the project folder directly.

Ensure:
Android SDK installed (Minimum SDK: API 21)
Gradle updates completed

Run on:
Android Emulator, or
Real Android Device (USB Debugging)


GitHub Repository
Official Project URL:
https://github.com/haziqnajibmokhtar/DividendCalculator

Create & Push to GitHub (Commands)
# In the project root folder
git init
git add .
git commit -m "Initial commit: DividendCalculator App"

# Add your GitHub remote (replace with your repo URL)
git remote add origin https://github.com/haziqnajibmokhtar/DividendCalculator.git
git branch -M main
git push -u origin main
