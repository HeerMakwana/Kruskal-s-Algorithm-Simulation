# Kruskal-s-Algorithm-Simulation

# ⚡ PowerConnect: City Grid Optimization

PowerConnect is an interactive web-based simulation to optimize power distribution between cities using **Kruskal's Algorithm**. It allows users to generate random city networks or create custom ones and then visualize the Minimum Spanning Tree (MST) that connects all cities with minimal power usage.

## 🚀 Features

- 🔄 **Generate Random City Networks**: Automatically creates cities placed in a circular layout with random power connections.
- 🏙️ **Custom City Network**: Add, move, or delete cities and their power connections.
- 📈 **Visualized Kruskal’s Algorithm**: Step-by-step and animated simulation of MST formation.
- 🧠 **Smart Controls**:
  - Play, pause, resume algorithm animation.
  - Control animation speed.
  - View step-by-step edge selection and MST formation.
- 📊 **Real-time Statistics**: Displays current city count, total connections, and MST status.
- 🌙 **Dark Mode UI**: Beautifully themed interface with intuitive layout and modern design.

## 🧠 Algorithm Used

- **Kruskal’s Algorithm**: Greedy approach to find the MST.
  - Sorts all edges by weight.
  - Iteratively adds edges that don’t form cycles using Disjoint Set (Union-Find).

## 📂 File Structure

- `index.html`: Main file containing HTML, CSS styles, and JavaScript logic for the entire project.

## 🛠️ How to Run

1. Clone or download the repository.
2. Open `index.html` in any modern browser (Chrome/Firefox recommended).
3. Start experimenting with random or custom city networks.

## ✨ Demo Functionality

- Click “Generate Random Cities” to see automatic placement.
- Use “Run Algorithm” or “Next Step” to simulate the MST creation.
- Design your own cities in the “Custom City Network” tab and press “Use This Network” to simulate.

## 🎨 UI Technologies

- HTML5, CSS3 (Custom Dark Theme, Transitions, Animations)
- JavaScript (Canvas API for drawing, Kruskal’s Algorithm, Union-Find)

## 📌 Future Enhancements

- Export simulation as an image or video.
- Save and load custom networks.
- Add Prim’s algorithm for comparison.

---

