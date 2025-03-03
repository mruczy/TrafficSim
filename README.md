# TrafficSim

In development on UE 5.5

TrafficSim is a traffic simulator that models vehicle behavior on a road network. The project includes features such as collision detection, route planning, alternative pathfinding, and U-turn handling. The goal of the simulation is to realistically represent vehicle movement in a dynamic environment.

## Features

- **Collision Detection**: The system automatically detects potential collisions between vehicles and takes preventive actions.  
  ![Collision Detection](/demo/collision_detection.gif)

- **Alternative Route Planning**: In case of obstacles or collisions, vehicles can find a new route to their destination.  
  ![Route Alternative](/demo/route_alternative.gif)

- **Route to Destination**: An algorithm based on a road grid calculates the shortest or optimal route to the designated destination.  
  ![Pathfinding](/demo/pathfinding.gif)

- **U-Turn**: Vehicles can perform a U-turn in specific situations, such as when a road is blocked.  
  ![U-Turn](/demo/u_turn.gif)

- **Dynamic Traffic Management**: The Traffic Manager randomly spawns vehicles on the map and assigns them destinations. Upon reaching a destination, a new random destination is assigned.  

## How the Simulation Works

1. **Start**: The Traffic Manager generates vehicles at random starting points on the road grid and assigns them random destinations.
2. **Movement**: Vehicles move according to their designated routes, avoiding collisions and adapting to road conditions.
3. **Destination Reached**: Upon arriving at a destination, a vehicle is assigned a new random destination and continues moving.

link to files
https://drive.google.com/drive/folders/19JSEWMNLNoCn6M19nf5qYu0Fj40GTsoz?usp=sharing
