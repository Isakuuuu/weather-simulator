# Live Weather Simulator

## Repository

https://github.com/Isakuuuu/weather-simulator.git

## Description

For my final project, I want to create a live weather simulator using Python that takes real-world weather data from an API and uses it to generate an animated environment. 

## Features
- Live Weather Data
  - Use a weather API like Open-Meteo to retrieve current weather information    for a specific location, including precipitation, wind speed, and cloud cover.

- Rain Simulation
  - Use Pygame to create a particle system that generates falling rain, with the amount of rainfall changing depending on the weather data.

- Wind Effects
  - Use wind speed and direction from the API to control how the rain particles move across the screen.

- Atmospheric Effects
  - Change the background colors, lighting, and cloud effects depending on the current weather conditions.

- Weather Updates
  - Allow the user to refresh the weather data so the simulation can update when conditions change.

## Challenges
- Learning how to use an API in Python and how to read and use the data it returns.
- Figuring out how to convert real weather measurements into values that control the animation.
- Creating a particle system that can handle different weather conditions while maintaining good performance.
- Learning how to handle errors if the API is unavailable or the program can't retrieve weather data.

## Outcomes
Ideal Outcome:
  - A working weather simulator that retrieves current weather data and creates an animated environment showing those conditions. Ideally, user will be able to see changes in rainfall, wind, and atmosphere, with the option to refresh the weather data while the program is running.

Minimal Viable Outcome:
  - A working Pygame application that retrieves weather data for one location and uses precipitation and wind measurements to control a basic rain particle simulation. Even without all the atmospheric effects, the program should demonstrate how real-world data can be used to control a procedural animation.

## Milestones

- Week 1
  1. Learn how to use the Open-Meteo API and retrieve weather data using Python.
  2. Extract the weather information needed for the simulation.

- Week 2
  1. Create the Pygame window and build a basic rain particle system.
  2. Connect the precipitation and wind data to the rain animation.

- Week 3
  1. Add atmospheric effects such as clouds and changes in background lighting.
  2. Implement a way to refresh the weather data and handle connection errors.

- Week 4
  1. Test the program, fix bugs, and improve the overall performance.
  2. Finish the documentation and prepare the final project demonstration.