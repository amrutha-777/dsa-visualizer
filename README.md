# dsa-visualizer
Building an interactive web app to visualize core data structures and algorithms including Sorting (Bubble), Pathfinding (BFS), and Tree Traversals.   Designed reusable React components with animations and intuitive UI.

## 🚀 Features

### 📊 Sorting Algorithms
- **Interactive Number Input**: Enter custom comma-separated numbers or generate random arrays
- **Visual Animations**: Watch numbers being compared (red highlight) and swapped (orange highlight)
- **Algorithm Support**:
  - Bubble Sort with step-by-step comparisons
  - Merge Sort with divide-and-conquer visualization
- **Real-time Statistics**: Track comparisons and swaps as they happen
- **Speed Control**: Adjust animation speed from 100ms to 2000ms

### 🗺️ Pathfinding Algorithms
- **Closed Figure Maze**: Navigate through a structured maze with walls forming closed shapes
- **Algorithm Comparison**:
  - Breadth-First Search (BFS) - finds shortest path
  - Depth-First Search (DFS) - explores deeply before backtracking
- **Visual Feedback**: 
  - Blue cells show visited nodes
  - Yellow path highlights the final route
  - Real-time statistics for visited nodes and path length
- **Speed Control**: Customize animation speed for detailed observation

### 🌳 Tree Data Structures
- **Binary Search Tree**: Build balanced BST from input arrays
- **Tree Traversals**:
  - In-order (Left → Root → Right)
  - Pre-order (Root → Left → Right)
  - Post-order (Left → Right → Root)
- **Interactive Visualization**: Watch nodes being visited with color-coded animations
- **Real-time Results**: See traversal sequences as they're generated

## 🛠️ Tech Stack

- **Frontend**: React 18 with modern hooks
- **Build Tool**: Vite for fast development and building
- **Styling**: Custom CSS with modern design principles
- **Animations**: CSS transitions and JavaScript-controlled timing
- **Responsive Design**: Mobile-first approach with breakpoints

## 📦 Installation

1. **Clone the repository**
   bash
   git clone https://github.com/amrutha-777/dsa-visualizer.git
   cd dsa-visualizer


2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to see the application

## 🎯 Usage

### Sorting Visualizer
1. Enter numbers separated by commas (e.g., `64,34,25,12,22,11,90`)
2. Choose your sorting algorithm (Bubble Sort or Merge Sort)
3. Adjust the animation speed using the slider
4. Click "Start Sort" to watch the algorithm in action
5. Use "Random Numbers" to generate test data

### Pathfinding Visualizer
1. Select your pathfinding algorithm (BFS or DFS)
2. Adjust the animation speed for detailed observation
3. Click "Start Pathfinding" to watch the algorithm explore the maze
4. Compare different algorithms to see their exploration patterns
5. Use "Clear Path" to reset and try again

### Tree Visualizer
1. Enter numbers separated by commas to build a BST
2. Choose your traversal type (In-order, Pre-order, or Post-order)
3. Click "Start Traversal" to watch the algorithm visit nodes
4. Observe the traversal sequence being built in real-time

## 🏗️ Project Structure

```
src/
├── components/
│   ├── SortingVisualizer.jsx    # Number-based sorting with animations
│   ├── PathfindingVisualizer.jsx # Grid-based pathfinding algorithms
│   ├── TreeVisualizer.jsx       # Binary tree traversal visualization
│   └── NavBar.jsx              # Tab navigation component
├── utils/
│   ├── sorting.js              # Sorting algorithm implementations
│   ├── pathfinding.js          # BFS and DFS implementations
│   └── tree.js                 # Tree data structure and traversals
├── App.jsx                     # Main application component
├── main.jsx                    # React application entry point
└── index.css                   # Global styles and animations
```

## 🎨 Design Features

- **Modern UI**: Clean, card-based layout with subtle shadows and rounded corners
- **Smooth Animations**: CSS transitions for all state changes and highlights
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Color-Coded Feedback**: Intuitive color scheme for different algorithm states
- **Real-time Statistics**: Live updates of algorithm performance metrics

## 🔧 Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build production-ready application
- `npm run preview` - Preview production build locally

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Add New Algorithms**: Implement Quick Sort, Heap Sort, or other sorting algorithms
2. **Enhance Visualizations**: Add more interactive features or animation improvements
3. **Algorithm Optimizations**: Improve existing algorithm implementations
4. **UI/UX Improvements**: Enhance the user interface and experience
5. **Documentation**: Improve code comments and documentation

### Development Setup

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes and test thoroughly
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📚 Algorithm Complexity

| Algorithm | Time Complexity | Space Complexity | Stable |
|-----------|----------------|------------------|---------|
| Bubble Sort | O(n²) | O(1) | Yes |
| Merge Sort | O(n log n) | O(n) | Yes |
| BFS | O(V + E) | O(V) | - |
| DFS | O(V + E) | O(V) | - |

## 🎓 Educational Value

This visualizer is perfect for:
- **Computer Science Students**: Understanding algorithm behavior and complexity
- **Coding Interview Preparation**: Visualizing common algorithm questions
- **Teaching**: Demonstrating algorithms in classrooms or tutorials
- **Self-Learning**: Exploring how different algorithms solve problems

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Inspired by algorithm visualization tools and educational platforms
- Built with modern React patterns and best practices
- Designed with accessibility and user experience in mind



---

⭐ **Star this repository if you found it helpful!** ⭐


