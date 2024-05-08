# EVOPT-Maps

EVOPT Maps is a project developed as a university assignment for the "Intelligent Systems" course. The project leverages the osmnx library to implement real-world streets and simulate the journey of an electric vehicle.

## Introduction

EVOPT Maps aims to develop a system for electric vehicle charging. It provides a user-friendly interface for users to automatically locate and reserve charging stations. The project uses a search algorithm to find the most efficient route for the electric vehicle, considering factors such as distance, time, speed, and availability of charging stations. 

The search algorithm was chosen for several reasons. Firstly, it allows for the consideration of multiple factors in route selection, providing a more comprehensive solution than simple distance-based algorithms. Secondly, it is highly adaptable and can be easily adjusted to account for changes in road conditions or vehicle parameters.

## Features

- Downloads real-world maps with accurate information.
- Automates the process of searching and locating charging stations.
- Allows users to specify the desired battery percentage at the end of the journey.

## Installation

Follow these steps to install and run the EVOPT-Maps project:

1. Clone the repository: 

```bash
git clone https://github.com/PasticciniTeams/EVOPT-Maps.git
```

2. Install the required dependencies: 

```bash
pip3 install folium
pip3 install osmnx
pip3 install numpy
pip3 install geopy
pip3 install scikit-learn
pip3 install customtkinter
```
or

```bash
pip3 install folium osmnx numpy geopy scikit-learn customtkinter
```

3. Run the program: 

```bash
python3 gui.py
```

## Usage

1. Clone the repository to your local machine.
2. Install the necessary dependencies.
3. Run the program and specify the parameters for the vehicle and location.
4. The program will then download the map and find the best route for your vehicle.
5. Open path.html to view the map with the optimal route.

## UI examples

Here are some previews of the user interface:

![GUI preview](https://github.com/PasticciniTeams/EVOPT-Maps/blob/main/example/gui_example.png)
![MAPS preview](https://github.com/PasticciniTeams/EVOPT-Maps/blob/main/example/maps_example.png)

## Documentation

The documentation is available [here](https://raw.githack.com/PasticciniTeams/EVOPT-Maps/main/docs/_build/html/index.html).

## Contributors

- [Camossi Filippo](https://github.com/SickCiQuattro)
- [Cioli Daniele](https://github.com/Profect99)

## Note

[This file](https://github.com/PasticciniTeams/EVOPT-Maps/blob/old-algorithm/Search/electric_vehicle.py), originating from a previous branch, illustrates a modified version of the old A* based search algorithm 

## License

All resources used within the project are free license!
