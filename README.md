One advantage of digital buildings is that operational data is flowing and being recorded. This data is valuable for many purposes. One of them is fault detection on building energy systems.

You are provided with a time series of heating-related data from a single-family house in Denmark: Heat meter data for the house as a whole, the indoor air temperature in different rooms, and the set point and motor position of the thermostat in some rooms (active rooms). 

The active rooms were controlled with an MPC that varied the set point of the radiator to obtain demand response. But the controller was not stable all the time, which led to some issues with thermal discomfort.
Your task is to:

1. Write a rule that identifies situations with expected thermal comfort issues
2. Propose rules that make use of the data series to avoid these issues in the future. Make sure the rules "catch" all possible types and reasons for comfort violations
Report your findings by showing relevant time series plots and a description of proposed fault detection principles.
