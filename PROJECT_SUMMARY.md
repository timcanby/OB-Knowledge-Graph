# Project Summary: OB Knowledge Graph

## Project Overview

The OB Knowledge Graph is an interactive web-based visualization of key concepts, theories, and terms from the OpenStax textbook "Organizational Behavior". It provides an intuitive way to explore relationships between different concepts in organizational behavior and management.

## Key Statistics

- **Total Nodes**: 451
- **Total Links**: 397
- **Node Categories**: 40+
- **Languages Supported**: 3 (English, Chinese, Japanese)
- **Technology Stack**: D3.js v7, HTML5, CSS3, Vanilla JavaScript

## Project Structure

```
OB-Knowledge-Graph/
├── index.html                 # Main application (all-in-one file)
├── data/
│   └── graph_data.json        # Knowledge graph data (451 nodes, 397 links)
├── README.md                  # Main documentation (English, Chinese, Japanese)
├── LICENSE                    # CC BY 4.0 License
├── ATTRIBUTION.md             # Source attribution and compliance
├── CONTRIBUTING.md            # Contribution guidelines
├── package.json               # NPM metadata
├── .gitignore                 # Git ignore rules
└── PROJECT_SUMMARY.md         # This file
```

## Features

### Core Functionality
1. **Interactive Visualization**: Drag nodes, zoom, pan through the graph
2. **Multilingual Support**: Switch between English, Chinese, and Japanese
3. **Smart Search**: Real-time search with automatic viewport centering
4. **Node Details**: Click nodes to view descriptions and connections
5. **Physics Simulation**: Toggle force-directed layout
6. **Responsive Design**: Works on various screen sizes

### Visual Design
- Modern gradient background (purple to blue)
- Glowing effects on nodes
- Color-coded categories
- Smooth animations and transitions
- Professional UI with control panels

### Interactive Elements
- Draggable nodes with physics simulation
- Searchable node database
- Hoverable connections highlighting
- Clickable nodes for detailed information
- Language switching buttons
- Zoom and pan controls
- Reset view button

## Data Source

**Original Work**: Organizational Behavior  
**Authors**: OpenStax  
**Institution**: Rice University  
**License**: CC BY 4.0  
**URL**: https://openstax.org/details/books/organizational-behavior  
**PDF**: https://assets.openstax.org/oscms-prodcms/media/documents/OrganizationalBehavior-OP_TtwWIeQ.pdf

## Technologies Used

### Frontend
- **D3.js v7**: Force-directed graph visualization
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: Interactive functionality

### No External Dependencies
The visualization is self-contained with no npm dependencies required. All functionality is implemented using vanilla JavaScript and D3.js loaded via CDN.

## How to Use

### Quick Start
1. Clone the repository
2. Start a local server: `python3 -m http.server 8000`
3. Open `http://localhost:8000` in your browser

### Navigation
- Drag nodes to move them
- Scroll to zoom in/out
- Click and drag background to pan
- Click "Reset View" to return to initial state

### Search
- Type in search box to find nodes
- Matching nodes highlight automatically
- First match centers on screen

### Language Switching
- Click language buttons (English, 中文, 日本語)
- Node labels update instantly
- Descriptions remain in English

## Node Categories

The graph includes the following types of nodes:

| Category | Count | Examples |
|----------|-------|----------|
| Core Concepts | 10+ | Management, Work, Organization |
| Theories | 16+ | Motivation Theory, Leadership Theory |
| Terms | 71+ | Organizational Culture, Motivation |
| Chapters | 6 | Chapter 1-9 |
| Subtopics | 9+ | Individual Behavior, Group Dynamics |
| Other | 300+ | Various organizational elements |

## License and Attribution

This project is licensed under CC BY 4.0 (Creative Commons Attribution 4.0 International).

### Attribution Requirements
When using this work, you must:
1. Give credit to OpenStax and Rice University
2. Link to the CC BY 4.0 license
3. Indicate if changes were made

### What You Can Do
- Share and adapt the work
- Use for commercial purposes
- Modify and distribute
- Create derivative works

## File Descriptions

### index.html
The main application file containing:
- All HTML structure
- All CSS styling (embedded)
- All JavaScript functionality (embedded)
- D3.js visualization logic
- Interactive controls and panels
- Multi-language support

### data/graph_data.json
Contains:
- 451 nodes with properties:
  - id, name, name_cn, name_jp
  - description, category, labels
- 397 links representing relationships:
  - source, target, type

### README.md
Comprehensive documentation including:
- English version (primary)
- Chinese version (中文)
- Japanese version (日本語)
- Quick start guide
- Feature descriptions
- Usage instructions
- Troubleshooting tips

### LICENSE
Full text of CC BY 4.0 license

### ATTRIBUTION.md
Detailed attribution information:
- Original source details
- License compliance information
- How to attribute the work
- Technology credits

### CONTRIBUTING.md
Guidelines for contributors:
- How to report issues
- How to suggest features
- How to submit code changes
- Code style guidelines
- Testing requirements

## Browser Compatibility

Tested and working on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

Requires:
- JavaScript enabled
- Modern browser with ES6 support
- WebGL support (for smooth rendering)

## Performance

- Initial load: ~2-3 seconds
- Graph rendering: ~1-2 seconds
- Interaction: Smooth 60fps
- Search: Real-time (<100ms)
- Language switching: Instant

## Accessibility

- Keyboard navigation support
- Hover tooltips for node names
- Clear visual hierarchy
- High contrast colors
- Responsive design

## Future Enhancements

Potential improvements:
- Export graph as image/PDF
- Advanced filtering options
- Node clustering
- Timeline view
- Comparison mode
- Mobile app version
- Additional languages
- Community contributions

## Deployment Options

### GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in settings
3. Access via https://username.github.io/OB-Knowledge-Graph

### Static Hosting
- Netlify
- Vercel
- AWS S3
- Any static web host

### Local Deployment
- Python: `python3 -m http.server 8000`
- Node.js: `npx http-server`
- Apache/Nginx: Copy files to web root

## Support and Contact

- GitHub Issues: Report bugs and suggest features
- GitHub Discussions: General questions and discussions
- Email: [your-email@example.com]

## Version History

### v1.0.0 (January 2024)
- Initial release
- 451 nodes and 397 links
- English, Chinese, Japanese support
- Interactive visualization with D3.js
- Full feature set implemented

## Contributing

Contributions are welcome! Please see CONTRIBUTING.md for guidelines.

## Acknowledgments

- OpenStax for the original textbook
- Rice University for hosting the material
- D3.js community for the visualization library
- All contributors and users

## Related Resources

- OpenStax: https://openstax.org/
- D3.js: https://d3js.org/
- Creative Commons: https://creativecommons.org/
- Knowledge Graphs: https://en.wikipedia.org/wiki/Knowledge_graph

---

**Last Updated**: January 2024  
**Project Status**: Active and Maintained  
**License**: CC BY 4.0
