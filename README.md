# TAB D20 Dice Roller & Combat Companion
A versatile, multi-language web application designed for tabletop RPG players. It features a comprehensive dice roller and an intuitive combat tracker to manage character and enemy stats during gameplay.

## About The Project
This project was born out of the need for a simple, yet powerful, tool for tabletop role-playing games like Dungeons & Dragons. Many existing tools are either too complex or lack essential features. This application aims to provide a streamlined experience, combining a flexible dice roller with a detailed combat assistant in a single, easy-to-use interface.
The application is a single, self-contained HTML file, making it incredibly portable and easy to run in any modern web browser without the need for a server or complex setup.

## Key Features
### Multi-Language Support: Fully localized interface supporting English, Italian, Spanish, French, and German.

### Advanced Dice Roller:
Roll any number of dice (1-100) of standard types (d4, d6, d8, d10, d12, d20, d100). Displays the total result and a detailed breakdown of individual rolls.

### Intuitive Combat Helper:
Track stats for both the Hero and an Enemy. Hero Stats: Manage Health, Attack, Weapon, Defense, Armor, Coins, Notes, and status effects like Poison and Bleed. Potion System: Use potions to restore health and cleanse negative effects. Enemy Stats: Track Health, Attack, Defense, and the Poison/Bleed values they apply on successful hits.

### Dynamic Combat Log:
Get real-time, detailed feedback for every action in combat.
Logs include attack rolls, damage calculation, defense rolls, armor absorption, and status effect applications.

### Roll History:
Keeps a timestamped log of all dice rolls made during the session.
The history can be cleared at any time.

### Sleek & Responsive UI:
Modern, dark-themed interface built with Tailwind CSS.
Fully responsive design for seamless use on desktop, tablets, and mobile devices.

### Zero Dependencies: Runs entirely in the browser. Just open the HTML file to get started.
Built With
This project is built with modern web technologies, focusing on simplicity and performance.
```
HTML5
Tailwind CSS
Vanilla JavaScript
```
Getting Started
To get a local copy up and running, simply download the index.html file and open it in your favorite web browser.

Translations
To add a new language or modify existing translations, edit the translations object within the <script> tag. Create a new entry with the two-letter language code and provide the key-value pairs for all UI elements and log messages.

## Usage
Language Selection: Upon first launch, you will be prompted to select your preferred language.
Dice Roller Tab: The default view. Select the number of dice and the dice type, then click "Roll!". The result and a detailed breakdown will appear below.
Combat Helper Tab: Switch to this tab to manage a combat encounter.
Input the initial stats for your Hero and the Enemy.
Use the + and - buttons for quick adjustments or click on the number to open a modal for larger changes.
Use the "Hero Attacks" and "Enemy Attacks" buttons to simulate combat rounds. The results will be printed in the Combat Log.
Use the potion button (▶) to restore the hero's health and remove status effects.
History: All rolls (from both the dice roller and combat) are logged in the "Roll History" section for easy reference.

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.
