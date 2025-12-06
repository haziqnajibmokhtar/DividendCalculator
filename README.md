# DividendCalculator (Android - Java)

Simple Android application to calculate monthly and total dividends from an invested fund.

## Features
- Accepts invested fund amount, annual dividend rate (%), and number of months (max 12).
- Calculates:
  - `monthlyDividend = (rate / 100 / 12) * amount`
  - `totalDividend = monthlyDividend * months`
- Displays results formatted to 2 decimal places.
- About page with author info and GitHub link.

## Author
Adam Bin Ali  
Matric no: 1234  
Course: ISP550

## How to build & run
1. Open Android Studio.
2. `File` → `New` → `Import Project` and select this project folder (or open the folder).
3. Make sure your SDK and gradle are up to date. Minimum SDK is API 21.
4. Run on emulator or device.

## GitHub
This README contains a placeholder repository URL: `https://github.com/yourusername/dividendcalculator`. Follow instructions below to create the repo and push.

## Create GitHub repository (example commands)
```bash
# in project root
git init
git add .
git commit -m "Initial commit: DividendCalculator"
# create a repository on GitHub (via website) and copy HTTPS URL, then:
git remote add origin https://github.com/yourusername/dividendcalculator.git
git branch -M main
git push -u origin main
