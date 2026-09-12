<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# [Project Name] 🎯
  water drop counter


## Basic Details
   A lightweight Arduino project that registers touch inputs using hardware interrupts and displays a real-time count on an SH1106 SPI OLED display.
### Team Name: [goku]


### Team Members
- Team Lead: [Anurudh Babu] - [ace]
- Member 2: [Name] - [College]
- Member 3: [Name] - [College]

### Project Description
[2-3 lines about what your project does]
This project is a simple Touch Sensor Counter built using an Arduino, a 16×2 LCD display, and a touch sensor module.

The system detects each touch and automatically increases the counter. The current number of touches is displayed on the LCD in real time.

### The Problem (that doesn't exist)
[What ridiculous problem are you solving?]
The classic tech-project drift: we started out trying to electrocute falling water droplets with two loose wires, got trapped in LCD contrast purgatory, pivoted to an OLED display, and ended up building an over-engineered touch-counting machine

### The Solution (that nobody asked for)
[How are you solving it? Keep it fun!]
By leaning entirely into the chaos of trial-and-error engineering. Instead of treating it like a rigid textbook build, we’re treating it like a mad-scientist lab where every failed wire, stubborn LCD box, and sudden pivot from water physics to digital touch is just part of the plot.

## Technical Details
### Technologies/Components Used
For Software:
- c++
- U8g2
- Arduino ide
  

For Hardware:
- Arduino
- touch sensor
- olede sh 1106


### Implementation




# Screenshots (Add at least 3)
![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

# Diagrams
![Workflow](Add your workflow/architecture diagram here)
*Add caption explaining your workflow*

For Hardware:

# Schematic & Circuit
+-------------------------------------------------------------+
|                         ARDUINO UNO                         |
|                                                             |
|   [GND] -------+-----------------+                          |
|                |                 |                          |
|   [5V]  -------+-------+         |                          |
|                |       |         |                          |
|   [Pin 2] <----+       |         |                          |
|   [Pin 8] <------------+--[RES]  |                          |
|   [Pin 9] <------------+---[DC]  |                          |
|   [Pin 10] <-----------+---[CS]  |                          |
|   [Pin 11] <-----------+---[D1]  |  (SH1106 SPI OLED)       |
|   [Pin 13] <-----------+---[DP]  |                          |
+-------------------------------------------------------------+
                 |       |         |
                 |       |         +-- OLED VCC
                 |       +------------ OLED GND
                 +-------------------- Touch Sensor SIG & VCC/GND
# Build Photos
![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

### Project Demo
# Video
[Add your demo video link he

https://github.com/user-attachments/assets/b31c219b-b172-438b-971f-e34d397d9fd5

re]
*Explain what the video demonstrates*

# Additional Demos
[Add any extra demo materials/links]


Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



