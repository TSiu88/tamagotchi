# _Tamagotchi_

#### _Exercise in Timers, 02.10.2020_

#### By _**Tiffany Siu and Adela Darmansyah**_

[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
![LastCommit](https://img.shields.io/github/last-commit/tsiu88/wordcounter-csharp)
![Languages](https://img.shields.io/github/languages/top/tsiu88/wordcounter-csharp)
[![MIT license](https://img.shields.io/badge/License-MIT-orange.svg)](https://lbesson.mit-license.org/)

---
## Table of Contents
1. [Description](#description)
2. [Setup/Installation Requirements](#setup/installation-requirements)
    - [Requirements to Run](#requirements-to-run)
    - [Instructions](#instructions)
    - [Other Technologies Used](#other-technologies-used)
3. [Specifications](#specifications)
4. [Known Bugs](#known-bugs)
5. [Support and Contact Details](#support-and-contact-details)
6. [License](#license)
---

## Description

This program uses timers to create tamagotchis that decrease in stats over time and the user tries to keep them alive by feeding, playing, and keeping the baby happy and healthy.

## Setup/Installation Requirements

### Requirements to Run
* _Web Browser_
* _Webpack_
* _Node.js_
* _NPM_

### Instructions

*This page may be viewed by:*

1. Download and install Node.js from the [official website](https://nodejs.org/en/download/)
2. Clone the repository [here](https://github.com/TSiu88/tamagotchi.git) or [here](https://github.com/Ayohana/tamagotchi.git) from either this [GitHub page](https://github.com/TSiu88) or that [GitHub page](https://github.com/Ayohana)
3. Use a command line/Bash to move to the project directory with `cd into-project-directory`
4. Run `npm install` to get all dependencies. 
5. Run `npm run start` to start up the program

## Other Technologies Used

* _HTML_
* _CSS_
* _Javascript_
* _JQuery 3.4.1_
* _Bootstrap 4.4.1_
* _ESLint_
* _Babel_
* _Jest_
* _Markdown_

## Specifications

* _The program was created with a tamagotchi object_
  * _Example Input: start program_
  * _Example Output: tamagotchi created_
* _The program has a timer that decreases levels for the tamagotchi._
  * _Example Input: time: -5 secs_
  * _Example Output: energy -10, hunger +15, fatigue +5, happiness -5_
* _Player clicks "feed" to decrease hunger level and increase energy level_
  * _Example Input: click "feed"_
  * _Example Output: hunger -25, energy+10_
* _Player clicks "play" to increase happiness level and decrease energy level_
  * _Example Input: click "play"_
  * _Example Output: happiness + 20, energy -15_
* _Player clicks "sleep" to decrease fatigue level and increase energy level_
  * _Example Input: click "sleep"_
  * _Example Output: fatigue level=0, energy +20, time=20secs passed_
* _If stat is outside the normal range for that stat, set stat to the limit instead_
  * _Example Input: -5_
  * _Example Output: 0_
* _If any of the stats are within 10 points from the limit, warning that pet may die will show_
  * _Example Input: energy=10, hunger=90, fatigue=30, happiness=40
  * _Example Output: "Warning! Pet may die!"
* _If any of the stats reaches the limit, pet dies_
  * _Example Input: energy=30, hunger=100, fatigue = 40, happiness=0
  * _Example Output: Alert "Pet has died."

## Known Bugs

_There are currently no known bugs in this program_

## Support and contact details

_If there are any question or concerns please contact me at our email [here](mailto:tsiu88@gmail.com) or [here](mailto:adela.yohana@gmail.com). Thank you._

### License

*This software is licensed under the MIT license*

Copyright (c) 2020 **_Tiffany Siu, Adela Darmansyah_**
