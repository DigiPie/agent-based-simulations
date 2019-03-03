# agent-based-simulations
Agent-based-simulations using AnyLogic

## Schelling Segregation model
This is a [Schelling Segregation model](https://lectures.quantecon.org/jl/schelling.html) of household movements in the context of humans, orcs, elves and dwarves.

### Properties
* Timescale is in Years.
* Household agents are either in Happy or Unhappy state. Every year, this state is updated with the following rules:
  * Human and elf households are Happy when at least 3 neighbours are of the same race.
  * Orc and dwarf households are Happy when at least 2 neighbours are of the same race.
* Every year, all Unhappy households jump to new random positions.

### Preview
![](schelling_segregation/schelling_segregation.gif)

### Usage
1. Download [schelling_segregation.alp](schelling_segregation/schelling_segregation.alp)
2. Open and run the model using [AnyLogic](https://www.anylogic.com/downloads/)
