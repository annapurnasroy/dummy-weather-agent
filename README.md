# Dummy Weather Agent 🌦️

## Overview
This project demonstrates the basic working of an AI agent using Python and the Open-Meteo Weather API. It is a beginner-friendly implementation of the Thought–Action–Observation cycle.

## Objectives
- Understand the basic workflow of an AI agent.
- Integrate an external weather API using Python.
- Execute a tool and collect its output as an observation.
- Display the result as a final answer.

## Technologies Used
- Python
- Open-Meteo Weather API
- Requests library
- Google Colab

## Agent Workflow
1. **Thought:** Identify the information required.
2. **Action:** Call the `get_weather()` function.
3. **Observation:** Receive the weather data from the API.
4. **Final Answer:** Display the retrieved weather information.

## Features
- Retrieves current temperature.
- Retrieves relative humidity.
- Retrieves wind speed.
- Supports configured cities such as Kolkata, Delhi, Mumbai, and Chennai.
- Uses Open-Meteo without requiring an API key for eligible use.

## Example Output
Weather in Kolkata:
- Temperature: 32.5 °C
- Humidity: 53%
- Wind speed: 8.4 km/h

*Example output only; actual values change with weather conditions.*

## How to Run
1. Open the project notebook in Google Colab.
2. Run the cell containing the `get_weather()` function.
3. Run the cell containing the `dummy_agent()` function.
4. Call the agent with a city name.

## Limitations
This is a rule-based dummy agent. Python controls the workflow, and the agent does not yet use an LLM to select tools dynamically. Weather availability depends on the external API and internet connectivity.

## API Reference
[Open-Meteo Documentation](https://open-meteo.com/en/docs)

## Learning Outcome
This project provides practical experience with API integration, Python functions, tool execution, and the Thought–Action–Observation cycle.
