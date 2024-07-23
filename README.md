 Automatic Rain Sensing Wipers Using Arduino

## EC280 Mini-Project in Circuits and Systems

### Submitted in partial fulfillment of the requirements for the degree of Bachelors of Technology

### Authors
- Bysani Abhinav (221EC210)
- Yashwanth K R (221EC264)

### Supervised by
Dr. Sushil Kumar Pandey  
Department of Electronics and Communication Engineering  
National Institute of Technology Karnataka (NITK), Surathkal, Mangalore - 575 025  

## Abstract

Driver safety is a top priority in the automotive industry. Heavy rain and lack of visibility are major causes of accidents. Manual errors, such as not adjusting wiper speed, can lead to accidents. Current car wipers require manual operation. This project proposes an automated wiper system with a rain sensor that detects rain and automatically adjusts wiper speed based on the intensity of the rain. This system uses an Arduino, a rain sensor, and a servomotor to automate the wiper operation, ensuring improved safety without manual intervention.

## Contents

1. Introduction
2. Motivation
3. Objectives
4. Literature Review
5. Methodology
6. Results
   - 6.1 Work Done
   - 6.2 Discussions
7. Conclusion
   - 7.1 Future Work
   - 7.2 References

## List of Figures

- Figure 1: Relationship of rainfall and rain crash effect.
- Figure 2: Arduino Uno
- Figure 3: Rain sensor
- Figure 4: Servo motor
- Figure 5: Case 1
- Figure 6: Case 2
- Figure 7: Case 3
- Figure 8: Case 4

## Introduction

A car wiper removes raindrops from the windshield to prevent accidents. Current wipers require manual operation to start and adjust speed. This project proposes an automated wiper system using a rain sensor and Arduino to detect rain and adjust wiper speed accordingly, ensuring driver safety without manual intervention.

## Motivation

According to the World Health Organization, over 2 million people die in accidents annually during the rainy season. The National Highway Traffic Safety Administration (NHTSA) reports that 70% of weather-related car accidents are due to wet pavement, with rain responsible for 46% of such incidents. This project aims to reduce accidents by automating wiper control, ensuring drivers can focus on the road.

## Objectives

- Investigate and evaluate various rain sensors.
- Design a user-friendly interface with LCD or LED indicators.
- Allow customization of wiper settings.
- Introduce redundancy to avoid errors.
- Design a speed-controlled wiper mechanism and alert system.

## Literature Review

- **Optical Rain Sensors:** Detect water droplets using infrared light.
- **Capacitive Rain Sensors:** Measure changes in capacitance due to water.
- **Acoustic Rain Sensors:** Use sound waves to detect raindrops.
- **Piezoelectric Rain Sensors:** Generate electric charge in response to mechanical stress from raindrops.

## Methodology

The system includes an Arduino Uno, rain sensor, servomotor, and LCD module. The rain sensor detects rain intensity and sends the information to the Arduino, which processes the data and controls the servomotor to adjust the wiper speed. The LCD displays the precipitation intensity.

### Block Diagram

![Block Diagram](https://github.com/YASHWANTHKR/Automatic-car-wiper-system-using-ardiunomm/blob/main/block%20diagram.png)

### Components

- **Arduino Uno:** Microcontroller board used for processing and controlling hardware.
- **Rain Sensor:** Detects raindrops and measures intensity.
- **Servo Motor:** Adjusts the wiper speed based on rain intensity.
- **LCD Module:** Displays precipitation intensity.

## Results
![No Rain](https://github.com/YASHWANTHKR/Automatic-car-wiper-system-using-ardiunomm/blob/main/first%20stage.jpg)
### Hardware Result

The LCD module displays precipitation intensity as zero, low, medium, or high. When it rains, the rain sensor detects the intensity and sends a signal to the Arduino, which adjusts the servomotor's rotation speed accordingly.

## Conclusion

The automatic wiper system detects rain and adjusts wiper speed without manual intervention, improving driver safety. The response time of the rain sensor to move the wiper is less than 400 ms. Future work includes replacing the rain sensor with an IR sensor for more accurate detection.
