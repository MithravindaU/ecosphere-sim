# 🌿 Ecosphere Sim

**A Grid-Based Agent Simulation Using Python, NumPy, and Matplotlib**

Ecosphere Sim is a lightweight, grid-based simulation that explores how independently moving agents behave inside a shared environment. It uses a two-dimensional world containing plants and herbivore agents, with random movement and visual tracking of spatial exploration.

The project is an introduction to agent-based modelling, stochastic processes, simulation design, and scientific visualisation.

## ✨ Features

- **Grid-based environment:** Represents a world as a 20 × 20 numerical grid.
- **Plant distribution:** Places plants at randomly selected grid locations.
- **Autonomous agents:** Simulates herbivores that move independently.
- **Boundary handling:** Keeps agents inside the environment.
- **Movement tracking:** Records agent visits to individual grid cells.
- **Exploration analysis:** Measures the number of unique cells visited.
- **Visual analytics:** Generates plots for movement, spatial visit frequency, and the final environment.
- **Reproducible experiments:** Uses a fixed random seed for repeatable results.

## 🧠 Technologies

| Technology | Purpose |
|---|---|
| Python | Simulation logic |
| NumPy | Grid and numerical operations |
| Matplotlib | Graphs and visualisation |
| Python `random` | Agent movement choices |
| Google Colab / Jupyter Notebook | Interactive execution |

## ⚙️ How It Works

1. Initialise a two-dimensional grid.
2. Distribute plants across the environment.
3. Place herbivore agents at random locations.
4. Move each agent using random horizontal and vertical steps.
5. Apply boundary constraints to keep agents inside the grid.
6. Record visited cells and cumulative movement.
7. Generate graphs and summarise the simulation.

## 📊 Visualisations

The simulation generates three figures:

- `movement_over_time.png`: Tracks the growth in the number of unique cells explored.
- `visited_cells_heatmap.png`: Shows the spatial frequency of agent visits.
- `simulation_final.png`: Displays plant locations and the final herbivore positions.

These visualisations describe agent movement and spatial exploration. They do not measure population health or ecological stability.

## 🚀 Getting Started

### Install dependencies

```bash
pip install numpy matplotlib
```

### Run the project

Open `ecosphere_sim version 1.ipynb` in Google Colab or Jupyter Notebook, then execute the simulation cells.

### Generated outputs

The notebook saves the graphs as PNG files. Download them and place them in the repository if you want them to appear in the README.

## 📐 Current Model

| Component | Current behaviour |
|---|---|
| Environment | Fixed-size 2D grid |
| Plants | Static locations |
| Herbivores | Random movement |
| Boundaries | Agents remain within the grid |
| Metrics | Unique cells visited and movement count |
| Visualisation | Final state and spatial exploration |

**Current limitation:** Plants are not consumed, and agents do not have energy, reproduction, or survival mechanics. The present version is a basic agent-movement simulation rather than a complete ecological model.

## 🔬 Future Improvements

- Plant consumption and regrowth
- Herbivore energy and survival mechanics
- Population changes over time
- Configurable simulation parameters
- Comparisons between random seeds and movement strategies
- Experiments measuring how environmental changes affect agent behaviour

## 🎯 Learning Outcomes

- Grid-based environment modelling
- Agent-based simulation fundamentals
- Randomised and stochastic behaviour
- State tracking and numerical analysis
- Scientific data visualisation
- Reproducible computational experiments

## 👩‍💻 Author

Mithravinda U

**Project category:** Simulation & Complex Systems  
**Repository:** [ecosphere-sim](https://github.com/MithravindaU/ecosphere-sim)
