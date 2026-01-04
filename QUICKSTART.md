# Quick Start Guide

## Installation

### Option 1: Online (Fastest)
Open the live demo in your browser:
https://your-github-pages-url

### Option 2: Local Installation

#### Prerequisites
- Git (for cloning)
- Python 3 or Node.js (for local server)
- Modern web browser

#### Steps

1. Clone the repository
```bash
git clone https://github.com/yourusername/OB-Knowledge-Graph.git
cd OB-Knowledge-Graph
```

2. Start a local server

Using Python 3:
```bash
python3 -m http.server 8000
```

Using Node.js:
```bash
npx http-server
```

3. Open in browser
Navigate to: http://localhost:8000

## Basic Usage

### Navigating the Graph

**Drag Nodes**: Click and drag any node to move it around

**Zoom**: Use your mouse wheel to zoom in and out

**Pan**: Click and drag the background to move the entire view

**Reset**: Click the "Reset View" button to return to the starting position

### Searching for Concepts

1. Type in the search box at the top-left
2. Matching nodes will be highlighted
3. The view automatically centers on the first match
4. Clear the search to see all nodes again

### Viewing Node Details

1. Click on any node
2. A panel appears on the bottom-right with:
   - Full node name
   - Description
   - Category
   - Number of connections

3. Click the X button to close the panel

### Changing Languages

Click one of the language buttons at the top-left:
- **English**: English labels
- **中文**: Chinese labels
- **日本語**: Japanese labels

The node labels update instantly!

### Physics Simulation

Click "Toggle Physics" to:
- Enable: Nodes move and settle naturally
- Disable: Nodes stay in place (useful for presentation)

## Tips for Best Experience

1. Use a modern browser (Chrome, Firefox, Safari, Edge)
2. Desktop or laptop recommended for best experience
3. Enable JavaScript in your browser
4. Use full-screen mode (F11) for immersive viewing
5. Clear browser cache if you see old data

## Troubleshooting

### Graph not loading?
- Check browser console (F12) for errors
- Ensure you have internet connection
- Try clearing cache and reloading (Ctrl+Shift+R)

### Nodes not moving?
- Check that physics is enabled
- Try clicking "Reset View"
- Refresh the page

### Search not working?
- Verify the search term exists
- Try searching in different languages
- Check browser console for errors

## Next Steps

- Explore the graph and discover relationships
- Read the full README.md for detailed documentation
- Check CONTRIBUTING.md if you want to help improve the project
- Visit the GitHub repository for more information

## Need Help?

- Open an issue on GitHub
- Check the FAQ section in README.md
- Review CONTRIBUTING.md for contact information

Enjoy exploring organizational behavior concepts!
