# IN CLASS COMPETITION: NEURAL NETWORK

The coal mill is an essential auxiliary system in a thermal power plant. Its main job is to grind chunks of coal into fine powder that meets the required specs. This powdered coal is then carried by the primary air fan into the furnace, where it burns and heats water into superheated steam. That steam is what drives the turbine to generate electricity.

For this experiment, we’re using steady-state data from a medium-speed coal mill at a certain power plant. The parameters we've extracted include:
1. Coal mill current (in amps): This indicates how much electrical current the mill is drawing. Assuming voltage and power factor stay the same, it reflects the power consumption.
2. Coal mill output (in tons per hour): This tells us how much qualified coal powder the mill is producing.
3. Primary air flow (in tons per hour): This is the amount of air going into the mill, which helps carry the coal powder into the furnace for combustion.
4. Primary air temperature (in °C): This is the temperature of the air entering the mill.
5. Primary air differential pressure (in kPa): This is the pressure difference between the air entering and exiting the mill, which can give insight into the airflow resistance.

In this task, you'll be using a neural network. The goal is to predict the coal mill current based on a selection of other parameters. You’re free to choose any combination of the input variables—except the current itself, of course—as your model inputs.
Note: Since we’re working with steady-state data, there’s no direct connection between one data point and the next. Each row of data stands alone.
