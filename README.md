# Animated Calorie Counter
This repository contains a Google Apps Script designed to animate a 'gold drop' (fat) effect in Google Sheets. The script is particularly tailored for a sheet setup where the animation simulates dropping gold into a jar represented by cells in the sheet.

![Screenshot 2023-11-30 170210](https://github.com/IanCKW/AnimatedCalorieCounter/assets/55784952/466ebfdd-63cf-449f-9149-4a50d032fb70)

## Features
- **Dynamic Animation:** Animates gold drops into a jar.
- **Customizable Parameters:** Allows for customization of key variables like the size of the jar, the number of gold cells, and more.
- **Ease of Use:** Designed to be integrated easily into existing Google Sheets with minimal setup.

## Setup
1. Open your Google Sheet.
2. Go to Extensions > Apps Script.
3. Copy and paste the script from `GoldDropScript.gs`.
4. Adjust the configuration variables as per your sheet's layout.

## Usage
- The script is triggered by the `dropGold()` function.
- Ensure your sheet matches the expected layout, particularly in terms of the jar's size and position.
