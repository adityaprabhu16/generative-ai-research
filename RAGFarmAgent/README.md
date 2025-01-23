# RAG FARMING AGENT

Note: I'm developing the following agent for the recent Ottomator hackathon. I'll update everyone on the results very soon!

Introduction:
For this Hackathon, my goal is to demo a robust Farming RAG agent that can pull data directly from two small greenhouses, despite the user being from anywhere in the world! 

Each greenhouse has a portable IoT sensor I programmed to report various environmental parameters. The n8n workflow then polls this documentation and the live greenhouse data spreadsheet for updates from the remote sensors, and can then analyze the data for you and give you insights and updates about how your plants are doing!

This documentation here is to share various different things you can ask the agent that would be of interest to an actual grower or farmer who are looking to automate insight generation from their IoT systems. 

Greenhouses:
Here’s some more information about the sensors in each greenhouse that the RAG agent will help monitor.

Tropical Greenhouse:
Refer to the greenhouse_data database for most recent information on relative humidity, temperature (temp), air pressure (pressure), battery, sensor name (tag), and timestamp.

The Tropical Greenhouse is aimed to emulate the environmental conditions of approximately the Kibara Plateau, DRC. This climate is known to be highland tropical, with seasonal variations in rainfall and temperature. Currently, this climate will be a bit cold and dry, and flora that grow on this plateau will often go into an obligate dormancy. A well known species from this region, also critically endangered, is the Drosera Katangensis, a unique stem-forming insectivorous plant with light cream-colored dewy leaves.


Mediterranean Greenhouse:
Refer to the greenhouse_data database for most recent information on relative humidity, temperature (temp), air pressure (pressure), battery, sensor name (tag), and timestamp.

The Mediterranean greenhouse is aimed to emulate the environmental conditions of approximately the coastal plains of Perth, Australia. This climate is known to have dry summers with little rainfall, and cooler wetter winters. Currently, the climate is a bit cold and wet, and flora that grow on these plains tend to emerge from their tubers to begin their active growing season with the harsh summers behind them. A well known species from this region is the Drosera Aberrans, a tuberous insectivorous plant with dark jade colored leaves arranged in a rosette. This plant often has a distinct sweet fragrance.



Things you can ask the RAG Agent:
For some ideas to ask the RAG agent that a grower like me would be interested in, try the following:
What is the current temperature and humidity of the tropical greenhouse?
What is the average temperature of the Mediterranean greenhouse?
What is the most recent update from the Mediterranean greenhouse?

And so on!
