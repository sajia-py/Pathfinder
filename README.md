# Pathfinder
### **Roomba Pathfinding Project**

Hi there! I'm **Sajia Ashfaq**, and this is my implementation of a Roomba Pathfinding system using **Python**, **Pygame**, and the **A* algorithm**. 🚀

---

#### **📌 About the Project**
This project simulates a Roomba navigating through a grid-based environment with obstacles to reach its destination efficiently. It leverages the **A* pathfinding algorithm** to compute the optimal path while ensuring smooth movement and real-time collision handling. The system incorporates essential data structures to manage the environment, path, and movements effectively.

---

#### **✨ Features**
- **Grid Representation**: A dynamic grid-based environment defined by a 2D matrix.
- **A* Pathfinding Algorithm**: Calculates the shortest path from start to goal.
- **Collision Handling**: Ensures the Roomba avoids obstacles seamlessly.
- **Real-Time Movement**: Smooth and visually accurate movement using `pygame.math.Vector2`.
- **Interactive Visualization**: Watch the Roomba navigate the environment step-by-step.

---

#### **🛠️ Tech Stack**
- **Python**: Programming language for logic and computation.
- **Pygame**: Library for graphical representation and real-time simulation.
- **Pathfinding Module**: For efficient A* implementation.

---

#### **📂 Key Components**
1. **Environment Grid**:
   - A 2D list (`matrix`) representing walkable and non-walkable cells.
2. **Path Storage**:
   - The computed path is stored in a list for the Roomba's movement.
3. **Collision Management**:
   - Small rectangles (`pygame.Rect`) are used for fine-grained collision handling.
4. **Smooth Navigation**:
   - Leveraging `pygame.math.Vector2` for direction and movement.

---

#### **📈 Data Structures Used**
- **2D List**: Represents the grid for pathfinding.
- **Lists**: Stores paths and collision rectangles.
- **Vectors**: For direction and movement calculations.
- **Grid Wrapper**: Integrates the A* algorithm with the environment.
- **Rectangles**: Manage collisions and grid cell boundaries.

---

#### **💡 How to Run**
1. Clone the repository:  
   ```bash
   git clone https://github.com/sajiaashfaq/roomba-pathfinding.git
   ```
2. Install dependencies:  
   ```bash
   pip install pygame
   ```
3. Run the simulation:  
   ```bash
   python main.py
   ```

---

#### **🎯 What I Learned**
- Implementing and optimizing the A* pathfinding algorithm.
- Managing collision detection and resolution in real-time.
- The importance of data structures in building efficient systems.
- Visualizing algorithms using Pygame.

---

Feel free to explore, fork, or contribute! 😊  
For any feedback or suggestions, you can reach me at **sajiaashfaq@gmail.com**.

Happy coding! 💻✨
