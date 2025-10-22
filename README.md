
> Open this page at [https://tickleba.github.io/adam-n-rochies/](https://tickleba.github.io/adam-n-rochies/)

## Hey guys galls and maybe pals me and adam o sullivan are making a shake up
https://github.com/user-attachments/assets/4bb2bc3e-59d2-4a96-8d36-505821b5655d](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcTtDAu6BUWNlczo9HAKXfU29FKpy7zV2nuTuw0yY3VApmjYaSqREPwYIDVGlBIeRxqvZXsn-oTHgcD4gE1GjcPQScNs9p8jpYMsh2qTMA

1. Project Alignment with Requirements
The Spider Plant Monitoring project, using the pre-defined data streams, meets all the computational and structural requirements:
Requirement Area
Alignment with Spider Plant Project
Thematic Brief
Environmental Monitoring for Optimisation: The project monitors a plant's local environment (light and heat) to provide insights on how to optimise it for better growth.
Data Streams
Log two different data types: Logs Temperature (∘C) and Light Level (0-255) using the micro:bit V2's built-in sensors.
Autonomous Logging
The micro:bit's data logging feature allows it to log to its flash memory at regular intervals (e.g., every 5 minutes) for a period longer than one hour (e.g., 24 hours), without being connected to a computer.
User Interface
The project will use the LED matrix to show logging status (e.g., a "heart" when active, an "X" when stopped) and the A/B buttons to start/stop the log.
Data Export/Processing
The logged data is exported to a CSV. A Python script (using Pandas/Matplotlib) will easily read this to perform the required calculation (e.g., maximum temperature achieved) and visualisation (e.g., a line graph of temperature and light over time).
Optimisation Goal
Biological Growth: Spider plants have known optimal conditions. The project aims to identify when the environment falls outside these ranges to suggest improvements (e.g., moving the plant, adjusting curtains).

Export to Sheets

2. Spider Plant Specifics for the Report
You can make your report strong by incorporating specific facts about the Spider Plant's ideal growing conditions into the Investigation and Plan section:
Condition
Spider Plant Optimum
Data Analysis Focus
Temperature
Ideal range is 18∘C to 29∘C (65∘F to 85∘F). They struggle below 10∘C and can be damaged above 35∘C.
Calculate the Total Time Spent Outside the Optimal Range (<18∘C or >29∘C).
Light Level
They prefer bright, indirect light. Direct, intense sunlight (high Light Level values) can scorch the leaves, while very low light causes the leaf variegation to fade.
Calculate the Range of Light Level Variability (Max - Min) to assess consistency and check for significant spikes (scorch risk).

Export to Sheets
Example System Requirement (for Section 1)
System Requirement: "The Micro:bit must log temperature in Celsius and Light Level at a regular interval of 5 minutes over a minimum period of 24 hours to capture a full day/night cycle of the Spider Plant's environment."
Example Recommendation (for Section 4)
Data Insight: "The data analysis showed the Spider Plant's light level consistently peaked between 11:00 and 13:00 with a reading above 200, coinciding with visible scorching on the leaves."
Recommendation: "Recommend adjusting the nearest window blinds or moving the plant 0.5 metres further away from the window to achieve the ideal bright, indirect light and reduce the peak Light Level by approximately 50%."

Spider plant
Humidity sensor 
Temperature sensor 
camera?
