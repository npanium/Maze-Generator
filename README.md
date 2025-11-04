# Maze Generator

A sleek, dark-themed maze generator with a modern glass morphism UI. Generate custom mazes with adjustable grid dimensions and solve them with A* pathfinding.

## Features

- **Adjustable Grid Size**: Customize maze dimensions with sliders (5-15 columns, 6-20 rows)
- **Maze Generation**: Recursive backtracking algorithm for perfect mazes
- **Pathfinding**: A* algorithm to find and highlight the optimal path
- **Path Isolation**: Remove all paths except the solution
- **Multiple Output Formats**:
  - Visual canvas representation
  - Text matrix output
  - JSON array format (copyable)

## How to Use

1. **Adjust Grid Size**: Use the sliders to set your desired columns and rows
2. **Generate Maze**: Click "Generate Maze" to create a new random maze
3. **Solve Maze**: Click "Solve & Isolate Path" to find and display only the solution path
4. **Copy Output**: Use the "Copy JSON Array" button to copy the grid data

## Output Format

The maze is represented as a 2D array where:
- `1` = Wall (black)
- `2` = Solution path (yellow)
- `0` = Walkable space (dark gray)

### Example JSON Output

```json
{
  "grid": [
    [1, 2, 1, 1, 1],
    [1, 2, 2, 2, 1],
    [1, 1, 1, 2, 1],
    [1, 1, 1, 2, 1]
  ]
}
```

## Design

- Dark, modern UI with glass morphism effects
- Green accent colors (#00ff88)
- System fonts for clean appearance
- Responsive layout
- Smooth animations and transitions

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Canvas-based visualization
- A* pathfinding algorithm
- Recursive backtracking maze generation

---

Built with vanilla JavaScript and modern CSS
