The aim of this project was to simulate flocking ai(crowd or herd) the agents in this case are fish
Currently there are no player interaction in this project but some interraction will be added later on.

They move to a target while considering others in their group
A group is created by calculating neigbours in a given radius and each agent moves according to their groups avarage forward vector while avoiding eachother
Agents also avoid obstacles with collision on them in this case pillars, trees, ground and castle
The goal of the group changes with a random value within the swimming bounds (+-(5,5,5)) and if a fish goes out of bounds, they will turn to the center of the flock until they can find a group.
Each fish created at the start and they are chosen randomly amoungst their type (2 possible colours in this case) until a maximum limit (200 for each schools in this case)
There are 2 different schools(400 fish) in here meaning there are 2 different goal locations

