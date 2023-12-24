Physarum Slime Mold expands by following the pheromone trails left by itself. In programming terms, there will be many agents exploring a bounded screen, those agents will be following the pheromone trails of previous agents. 

## Agents
### Description
Each Agent moves around the world depositing a pheromone trail. Each tick the agent moves a position ahead in the direction they are facing. They may also turn each tick with an increased likelihood to turn towards nearby pheromones the distance away from which is controlled by the vision factor. There is a slight chance that they will turn towards another direction controlled by the exploration factor. 
### Parameters
- Vision Factor
- Exploration Factor

## Pheromone
### Description
As each agent moves a Pheromone Trail is left behind. The pheromone trails can increase in density as more agents take that path, and over time the trail will fade via diffusion. Each tick the agent will deposit a point of pheromone at its current location with an initial strength value. Each subsequent tick that point of pheromone will diffuse by the diffusion factor, this diffusion will spread the pheromone pheromone to surrounding points whilst decreasing the strength of the diffusion in the current point until none remains. The spread is less than the amount of pheromone lost in the current point such that the pheromone doesn't continuously spread, this will be controlled by the loss factor. 
### Parameters
- Diffusion Factor
- Loss Factor
- Spread Factor
- Initial Strength
## The World
### Description
The World is set up into coordinate points. Each point will store a density of pheromone which Agents will use to determine movement. In the visualisation Pheromone density can be displayed via a colour spectrum. 

Each tick the current world state should also be saved, this will allow re-visualisation of a particular simulation. 
### Parameters
- Size
- Pheromone Density
- Time Between Ticks