<div align="center">

# 🔥 അഗ്നിപാതം

## Fire Evacuation Route Planner

### Intelligent Emergency Route Planning using A* Search & Fire Spread Simulation

#### A Python-Based Interactive System for Computing the Safest Building Evacuation Routes

<br>

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-FF6F00?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![A* Search](https://img.shields.io/badge/A*-Pathfinding-00599C?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Graph-Algorithms-228B22?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

# 📖 Overview

**അഗ്നിപാതം (Agnipatham) – Fire Evacuation Route Planner** is an intelligent emergency evacuation simulation that computes the safest path through a building during a fire emergency.

The system combines the **A\* Search Algorithm** with **dynamic fire spread simulation** to predict hazardous regions before route planning. Users can design building layouts, place walls, define fire sources, and visualize the safest evacuation path through an interactive graphical interface.

This project demonstrates practical applications of **Artificial Intelligence, Graph Search Algorithms, Simulation Systems, and Emergency Planning**.

---

# ✨ Features

- 🔥 Dynamic Fire Spread Simulation
- 🧭 Intelligent A* Pathfinding
- 🏢 Interactive Building Layout Editor
- 🚧 Custom Wall Placement
- 🎯 Configurable Start & Exit Points
- 📍 Real-Time Safe Route Visualization
- 🖥️ Interactive Tkinter GUI
- 🔄 Reset & Clear Simulation
- ⚡ Fast Route Computation

---

# 🏗️ System Architecture

The application follows a modular architecture that separates simulation, visualization, and path planning.

### 🖥️ User Interface

- Interactive grid-based building editor
- Mouse-driven wall placement
- Fire source configuration
- Start and destination selection

### 🔥 Fire Simulation Engine

- Predicts fire expansion
- Marks hazardous cells
- Prevents unsafe path generation

### 🧠 Path Planning Engine

- Implements the A* Search Algorithm
- Avoids walls and predicted fire zones
- Calculates the shortest safe evacuation route

### 📊 Visualization

- Displays obstacles
- Shows predicted fire spread
- Highlights the evacuation path
- Updates interactively

---

# 💻 Tech Stack

| Category | Technologies |
|----------|--------------|
| 🖥️ Programming Language | Python |
| 🧠 Algorithms | A* Search Algorithm |
| 🎨 GUI | Tkinter |
| 🔢 Numerical Computing | NumPy |
| 📈 Visualization | Matplotlib |
| 📦 Package Manager | pip |

---

# 🧠 Working Principle

The evacuation simulation follows four major stages.

## 1️⃣ Environment Creation

Users design the building layout by placing:

- Walls
- Fire Sources
- Starting Position
- Exit Location

---

## 2️⃣ Fire Spread Prediction

Before route planning, the simulator predicts how fire spreads to neighbouring cells.

These hazardous cells are marked as unsafe.

---

## 3️⃣ Safe Route Planning

The A* Search Algorithm evaluates every possible route while avoiding:

- Walls
- Fire
- Predicted Hazard Zones

The shortest safe evacuation path is selected.

---

## 4️⃣ Route Visualization

The computed evacuation path is displayed on the grid, providing a clear visual representation of the safest escape route.

---

# 📂 Project Structure

```text
Fire-Evacuation-Route-Planner
│
├── src/
│   ├── app.py
│   ├── astar.py
│   ├── fire.py
│   ├── gui.py
│   └── utils.py
│
├── main.py
├── requirements.txt
└── README.md
```

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/RijinRajeevan/Evacuation-Route-Planner.git

cd Evacuation-Route-Planner
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run the Application

```bash
python main.py
```

---

# 🎮 Usage

1. 🏢 Draw building walls.
2. 🔥 Place one or more fire sources.
3. 🟢 Select the starting position.
4. 🟡 Select the evacuation exit.
5. ▶️ Run the A* algorithm.
6. 🔵 Observe the safest evacuation route.
7. 🔄 Reset the environment for another simulation.

---

# 🎯 Applications

- 🏢 Smart Building Evacuation
- 🚒 Fire Safety Planning
- 🌍 Disaster Management
- 🤖 Robotics Path Planning
- 🧠 Artificial Intelligence Education
- 📚 Graph Algorithm Demonstration
- 🎓 Academic Projects
- 🚨 Emergency Response Simulation

---

# 📚 Concepts Demonstrated

- Graph Search Algorithms
- A* Search Algorithm
- Heuristic-Based Pathfinding
- Simulation Systems
- Hazard Prediction
- Grid-Based Navigation
- Human-Computer Interaction
- Event-Driven Programming

---

# 🚀 Future Enhancements

- 🤖 AI-Based Fire Prediction
- 🗺️ Multi-Floor Building Support
- 🚪 Multiple Exit Optimization
- 👥 Multi-Agent Evacuation
- 📊 Heatmap Visualization
- 🌐 Web-Based Dashboard
- 📍 Real Floor Plan Import
- 🤖 Reinforcement Learning Navigation
- 📱 Mobile Application

---

# 👨‍💻 Author

**Rijin Rajeevan**

B.Tech Computer Science & Engineering (Artificial Intelligence)

Amrita Vishwa Vidyapeetham

---

# 📜 License

This project is licensed under the **MIT License**.

See the **LICENSE** file for more information.
