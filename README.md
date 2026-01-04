# Organizational Behavior Knowledge Graph

<div align="center">

![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

**An Interactive Knowledge Graph Visualization of Organizational Behavior Concepts**

[English](#organizational-behavior-knowledge-graph) | [中文](#中文版) | [日本語](#日本語版)

</div>

---

## Overview

This project presents an **interactive knowledge graph visualization** of key concepts, theories, and terms from organizational behavior and management. The graph is extracted from the OpenStax textbook *Organizational Behavior* and provides an intuitive way to explore relationships between different concepts in the field.

### Key Features

- **Interactive Visualization**: Drag nodes, zoom, and pan through the knowledge graph
- **Multilingual Support**: Switch between English, Chinese (中文), and Japanese (日本語) with a single click
- **Smart Search**: Real-time search with automatic viewport centering
- **Node Details**: Click any node to view comprehensive descriptions and connections
- **Beautiful Design**: Modern UI with gradient backgrounds, glowing effects, and smooth animations
- **Physics Simulation**: Toggle force-directed layout for dynamic graph exploration
- **Responsive**: Works seamlessly on different screen sizes

---

## Quick Start

### Option 1: View Online (Recommended)
Simply open the [Live Demo](https://timcanby.github.io/OB-Knowledge-Graph/) in your browser. No installation required!

### Option 2: Local Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/timcanby/OB-Knowledge-Graph.git
   cd OB-Knowledge-Graph
   ```

2. **Start a local server**
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Or using Node.js
   npx http-server
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000` and enjoy!

---

## How to Use

### Navigation
- **Drag**: Click and drag any node to reposition it
- **Zoom**: Use mouse wheel or zoom buttons to zoom in/out
- **Pan**: Click and drag the background to pan the view
- **Reset**: Click the "Reset View" button to return to the initial view

### Search & Filter
- **Search**: Type in the search box to find nodes by name
- **Auto-Center**: Matching nodes automatically move to the screen center
- **Highlight**: Connected nodes are highlighted when you hover over them

### Language Switching
Click the language buttons at the top-left:
- **English**: View all labels in English
- **中文**: Switch to Chinese labels
- **日本語**: Switch to Japanese labels

### Node Information
- **Click** any node to view detailed information including:
  - Full name in all three languages
  - Comprehensive description
  - Category/Type
  - Number of connections

---

## Graph Statistics

| Metric | Value |
|--------|-------|
| **Total Nodes** | 451 |
| **Total Links** | 397 |
| **Node Categories** | 40+ |
| **Languages Supported** | 3 (English, Chinese, Japanese) |

---

## Project Structure

```
OB-Knowledge-Graph/
├── index.html              # Main visualization file (all-in-one)
├── data/
│   └── graph_data.json     # Knowledge graph data
├── README.md               # English documentation
├── README_CN.md            # Chinese documentation
├── README_JP.md            # Japanese documentation
├── LICENSE                 # CC BY 4.0 License
└── ATTRIBUTION.md          # Source attribution
```

---

## Data Source

This knowledge graph is extracted from:

> **Organizational Behavior** by OpenStax  
> Rice University  
> Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

**Original PDF**: [Organizational Behavior - OpenStax](https://assets.openstax.org/oscms-prodcms/media/documents/OrganizationalBehavior-OP_TtwWIeQ.pdf)

The graph represents the hierarchical relationships and interconnections between:
- Core concepts and theories
- Key terms and definitions
- Management functions and strategies
- Organizational factors and outcomes
- Individual and group behaviors

---

## Technologies Used

- **D3.js v7**: Force-directed graph visualization
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: Interactive functionality without dependencies

---

## Features in Detail

### 1. Interactive Force-Directed Layout
The graph uses D3.js's force simulation to create a natural, readable layout:
- Nodes repel each other to avoid overlap
- Links attract connected nodes
- Collision detection prevents node stacking
- Customizable physics parameters

### 2. Multi-Language Support
Each node contains labels in three languages:
- **English**: Primary language for descriptions
- **中文 (Chinese)**: Simplified Chinese translations
- **日本語 (Japanese)**: Japanese translations

Switch languages instantly without reloading the page!

### 3. Smart Search Algorithm
- Case-insensitive substring matching
- Searches across all three languages
- Auto-highlights all matching nodes
- Automatically centers the first match
- Real-time results as you type

### 4. Visual Hierarchy
Nodes are color-coded by category:
- **Core Concepts**: Bright cyan (#64c8ff)
- **Concepts**: Light cyan (#00d4ff)
- **Theories**: Red (#ff6b6b)
- **Terms**: Yellow (#ffd93d)
- **Other**: Green (#6bcf7f)

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Scroll` | Zoom in/out |
| `Drag Background` | Pan the view |
| `Click Node` | View node details |
| `Hover Node` | Highlight connections |

---

## Node Categories

The knowledge graph includes nodes from the following categories:

| Category | Count | Description |
|----------|-------|-------------|
| Core Concepts | 10+ | Fundamental principles |
| Theories | 16+ | Established frameworks |
| Terms | 71+ | Key terminology |
| Chapters | 6 | Textbook chapters |
| Subtopics | 9+ | Specialized topics |
| And more... | 300+ | Various organizational elements |

---

## Contributing

Contributions are welcome! Here's how you can help:

1. **Report Issues**: Found a bug or have a suggestion? [Open an issue](https://github.com/yourusername/OB-Knowledge-Graph/issues)
2. **Improve Translations**: Help improve Chinese or Japanese translations
3. **Enhance Features**: Suggest new visualization features
4. **Fix Bugs**: Submit pull requests with bug fixes

### Guidelines
- Keep commits atomic and descriptive
- Update documentation for new features
- Test changes in multiple browsers
- Maintain code style consistency

---

## License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

This means you are free to:
- Share and adapt the work
- Use it for commercial purposes
- Modify and distribute

**As long as you:**
- Give appropriate credit to OpenStax and Rice University
- Link to the license
- Indicate if changes were made

For more details, see [LICENSE](LICENSE) and [ATTRIBUTION.md](ATTRIBUTION.md).

---

## Attribution

**Original Work**: Organizational Behavior  
**Authors**: OpenStax  
**Institution**: Rice University  
**License**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)  
**Source**: [OpenStax Organizational Behavior](https://openstax.org/details/books/organizational-behavior)

**This Project**: Knowledge Graph Visualization  
**Purpose**: Educational visualization of OB concepts and relationships

---

## Related Resources

- [OpenStax Organizational Behavior](https://openstax.org/details/books/organizational-behavior)
- [D3.js Documentation](https://d3js.org/)
- [Creative Commons Licenses](https://creativecommons.org/)
- [Knowledge Graph Visualization Techniques](https://en.wikipedia.org/wiki/Knowledge_graph)

---

## Tips for Best Experience

1. **Use Modern Browser**: Chrome, Firefox, Safari, or Edge (latest versions)
2. **Desktop Recommended**: Best experience on desktop/laptop screens
3. **Enable JavaScript**: Required for interactive features
4. **Clear Cache**: If experiencing issues, clear browser cache and reload
5. **Full Screen**: Press F11 for immersive full-screen experience

---

## Troubleshooting

### Graph not loading?
- Check browser console (F12) for errors
- Ensure `data/graph_data.json` is accessible
- Try clearing cache and reloading (Ctrl+Shift+R)

### Nodes not dragging?
- Ensure JavaScript is enabled
- Try a different browser
- Check that physics simulation is enabled

### Search not working?
- Verify the search term exists in the graph
- Try searching in different languages
- Check browser console for JavaScript errors

---

## Support

- **Email**: [your-email@example.com]
- **Issues**: [GitHub Issues](https://github.com/yourusername/OB-Knowledge-Graph/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/OB-Knowledge-Graph/discussions)

---

## Educational Use

This visualization is designed for:
- Students studying organizational behavior
- Educators teaching OB concepts
- Professionals in HR and management
- Researchers in organizational studies

Feel free to use this in your educational materials!

---

<div align="center">

### If you find this project helpful, please consider giving it a star!

**Made with care for the organizational behavior community**

---

## Language Versions

- [English README](#organizational-behavior-knowledge-graph)
- [中文版 (Chinese)](#中文版)
- [日本語版 (Japanese)](#日本語版)

</div>

---

# 中文版

## 组织行为知识图谱

<div align="center">

**组织行为概念的交互式知识图谱可视化**

[English](#organizational-behavior-knowledge-graph) | [中文](#中文版) | [日本語](#日本語版)

</div>

### 项目概述

本项目呈现了一个**交互式知识图谱可视化**，展示了组织行为和管理学中的关键概念、理论和术语。该图谱从OpenStax教科书《组织行为》中提取，提供了一种直观的方式来探索该领域不同概念之间的关系。

### 主要功能

- **交互式可视化**：拖拽节点、缩放和平移知识图谱
- **多语言支持**：一键切换英文、中文和日文
- **智能搜索**：实时搜索并自动居中视图
- **节点详情**：点击任何节点查看详细描述和连接
- **精美设计**：现代UI设计，具有渐变背景、发光效果和流畅动画
- **物理模拟**：切换力导向布局以动态探索图谱
- **响应式设计**：在不同屏幕尺寸上无缝工作

### 快速开始

#### 选项1：在线查看（推荐）
直接在浏览器中打开[在线演示](https://timcanby.github.io/OB-Knowledge-Graph/)。无需安装！

#### 选项2：本地安装

```bash
# 克隆仓库
git clone https://github.com/timcanby/OB-Knowledge-Graph.git
cd OB-Knowledge-Graph

# 启动本地服务器
python3 -m http.server 8000

# 在浏览器中打开
# http://localhost:8000
```

### 使用指南

**导航操作**
- 拖拽：点击并拖动任何节点来重新定位
- 缩放：使用鼠标滚轮或缩放按钮
- 平移：点击并拖动背景来平移视图
- 重置：点击"重置视图"按钮返回初始视图

**搜索和过滤**
- 在搜索框中输入以查找节点
- 匹配的节点自动移动到屏幕中心
- 悬停时突出显示连接的节点

**语言切换**
点击左上角的语言按钮：
- **English**：英文标签
- **中文**：中文标签
- **日本語**：日文标签

### 图谱统计

| 指标 | 数值 |
|------|------|
| **总节点数** | 451 |
| **总连接数** | 397 |
| **节点类别** | 40+ |
| **支持语言** | 3种 |

### 数据来源

本知识图谱来自：

> **组织行为** 作者：OpenStax  
> 机构：莱斯大学  
> 许可证：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

**原始PDF**：[Organizational Behavior - OpenStax](https://assets.openstax.org/oscms-prodcms/media/documents/OrganizationalBehavior-OP_TtwWIeQ.pdf)

### 许可证

本项目采用**知识共享署名4.0国际许可证（CC BY 4.0）**。

您可以自由地：
- 分享和改编作品
- 用于商业目的
- 修改和分发

只要您：
- 给予OpenStax和莱斯大学适当的署名
- 链接到许可证
- 说明所做的更改

---

# 日本語版

## 組織行動知識グラフ

<div align="center">

**組織行動概念のインタラクティブな知識グラフ可視化**

[English](#organizational-behavior-knowledge-graph) | [中文](#中文版) | [日本語](#日本語版)

</div>

### プロジェクト概要

このプロジェクトは、組織行動と経営学における主要な概念、理論、用語の**インタラクティブな知識グラフ可視化**を提供します。このグラフはOpenStaxの教科書「組織行動」から抽出され、この分野のさまざまな概念間の関係を直感的に探索する方法を提供します。

### 主な機能

- **インタラクティブな可視化**：ノードをドラッグ、ズーム、パンして知識グラフを探索
- **多言語対応**：英語、中文、日本語をワンクリックで切り替え
- **スマート検索**：リアルタイム検索と自動ビューセンタリング
- **ノード詳細**：任意のノードをクリックして詳細説明と接続を表示
- **美しいデザイン**：グラデーション背景、グロー効果、スムーズなアニメーション
- **物理シミュレーション**：力指向レイアウトを切り替えて動的に探索
- **レスポンシブ**：さまざまな画面サイズで完璧に動作

### クイックスタート

#### オプション1：オンラインで表示（推奨）
ブラウザで[ライブデモ](https://timcanby.github.io/OB-Knowledge-Graph/)を開くだけです。インストール不要！

#### オプション2：ローカルインストール

```bash
# リポジトリをクローン
git clone https://github.com/timcanby/OB-Knowledge-Graph.git
cd OB-Knowledge-Graph

# ローカルサーバーを起動
python3 -m http.server 8000

# ブラウザで開く
# http://localhost:8000
```

### 使用方法

**ナビゲーション**
- ドラッグ：任意のノードをクリック＆ドラッグして移動
- ズーム：マウスホイールまたはズームボタンを使用
- パン：背景をクリック＆ドラッグしてビューを移動
- リセット：「ビューをリセット」ボタンをクリック

**検索とフィルター**
- 検索ボックスに入力してノードを検索
- マッチしたノードが自動的に画面中央に移動
- ホバー時に接続ノードがハイライト

**言語切換**
左上の言語ボタンをクリック：
- **English**：英語ラベル
- **中文**：中国語ラベル
- **日本語**：日本語ラベル

### グラフ統計

| メトリック | 値 |
|----------|-----|
| **総ノード数** | 451 |
| **総リンク数** | 397 |
| **ノードカテゴリ** | 40+ |
| **対応言語** | 3言語 |

### データソース

この知識グラフは以下から抽出されました：

> **組織行動** 著者：OpenStax  
> 機関：ライス大学  
> ライセンス：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

**元のPDF**：[Organizational Behavior - OpenStax](https://assets.openstax.org/oscms-prodcms/media/documents/OrganizationalBehavior-OP_TtwWIeQ.pdf)

### ライセンス

このプロジェクトは**クリエイティブ・コモンズ表示4.0国際ライセンス（CC BY 4.0）**の下でライセンスされています。

自由に：
- 作品を共有および改変
- 商用目的で使用
- 修正および配布

条件として：
- OpenStaxとライス大学に適切なクレジットを付与
- ライセンスへのリンク
- 変更内容を明示

---

<div align="center">

**このプロジェクトが役に立つ場合は、スターをお願いします！**

</div>
