# Fuzzy Logic Control: Automatic Door for Energy Efficiency
**Project by Akshata Gaikwad @ IIT Ropar**

## Objective:
To design an automatic door control system that provides for heat energy savings by adjusting opening speeds based on human walking speed and distance.

##  System Design
The model utilizes a Mamdani Inference Method to determine the optimal Door Opening Speed (DOS).

### Input Variables
* WS (Walking Speed): $0\text{--}50\text{ m/min}$.
* DD (Distance to Door): $0\text{--}6\text{ m}$.

### Output Variable
* DOS (Door Opening Speed): $0\text{--}500\text{ rpm}$.

## Mathematical Foundation
The crisp output $z^{*}$ is calculated using the Centroid (Center of Gravity) defuzzification method:

$$z^{*} = \frac{\sum \mu(\overline{z}) \cdot \overline{z}}{\sum \mu(\overline{z})}$$ 

where $\overline{z}$ is the distance to the centroid of the respective membership functions.

## Conclusion
Unlike classical systems that open at a constant speed, this fuzzy logic system adjusts the door range to prevent unnecessary heat loss.

---
*Supervised by Dr. Arvind Kumar as part of MA629.*
