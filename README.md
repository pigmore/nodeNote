# 🎯 NodeNote - Visual Idea Canvas

> **Freely place and connect your ideas** on an infinite canvas with this powerful, lightweight note-taking application
> built entirely with **vanilla JavaScript**.

![NodeNote Demo](https://img.shields.io/badge/Demo-Live-brightgreen)
![JavaScript](https://img.shields.io/badge/Built%20with-Vanilla%20JS-yellow)
![License](https://img.shields.io/badge/License-MIT-blue)
![One Page](https://img.shields.io/badge/Type-Single%20Page%20App-orange)

---

## ✨ **What is NodeNote?**

NodeNote is a **one-page application** that transforms the way you capture, organize, and connect your thoughts. Built
with pure **vanilla JavaScript**, it provides an infinite canvas where you can **freely place nodes anywhere** and
**connect them with beautiful curves** to visualize relationships between your ideas.

Perfect for:

- 🧠 **Mind mapping** and brainstorming
- 📋 **Project planning** and workflow design
- 🎓 **Study notes** and concept mapping
- 💡 **Creative ideation** and visual thinking
- 🏗️ **System architecture** diagrams

---

## 🚀 **Key Features**

### 📍 **Infinite Canvas**

- **Unlimited workspace** - zoom and pan anywhere
- **Smooth interactions** with mouse wheel zoom and drag-to-pan
- **Grid background** with adaptive scaling
- **Reset to home** functionality

### 🎨 **Flexible Nodes**

- **Two shapes**: Rounded rectangles and perfect circles
- **Customizable sizes** with drag-to-resize handles
- **Adjustable font sizes** (8px - 24px)
- **Border toggle** for clean, minimalist designs
- **Circle radius control** for perfect proportions
- **Double-click text editing** with live preview

### 🔗 **Beautiful Connections**

- **Bezier curve links** with smooth, natural flow
- **Directional arrows** positioned at curve midpoints
- **Curve customization**:
  - 📏 **Strength control** (0-100%)
  - 🎭 **Style presets** (Straight, Gentle, Strong)
  - 🎯 **Manual control points** for precise positioning
- **Arrow direction toggle** (A→B or A←B)
- **Smart curve updates** when nodes move

### ⚡ **Powerful Interactions**

- **Drag & Drop**: Move nodes freely around the canvas
- **Click to Select**: Visual feedback with green highlights
- **Properties Panel**: Context-sensitive controls
- **Keyboard Shortcuts**:
  - `Ctrl+Z` / `Cmd+Z` - Undo
  - `Ctrl+Shift+Z` / `Cmd+Shift+Z` - Redo
  - `Delete` / `Backspace` - Remove selected items
  - `Double-click` - Edit node text

### 📚 **Advanced History System**

- **50-state undo/redo** with full state restoration
- **Visual history panel** showing all actions
- **Click-to-jump** navigation to any previous state
- **Smart state tracking** (content only, not UI selections)
- **Branching support** for non-linear editing

### 💾 **Data Management**

- **Export projects** as JSON files with full fidelity
- **Import projects** with complete state restoration
- **Auto-saves** all customizations and relationships
- **Cross-platform compatibility**

---

## 🎮 **How to Use**

### **Getting Started**

1. **Add Nodes**: Click the large green `+` button (bottom-right)
2. **Create Links**: Click the purple `🔗` button, then click two nodes
3. **Edit Text**: Double-click any node to edit its text
4. **Customize**: Select items to open the properties panel

### **Navigation**

- **Mouse Wheel**: Zoom in/out
- **Drag Canvas**: Pan around the infinite workspace
- **Reset View**: Click the home `⌂` button

### **Advanced Features**

- **History Panel**: Click `📜` to see your edit timeline
- **Properties Panel**: Auto-appears when items are selected
- **Export/Import**: Use `💾` and `📁` buttons in top-right

---

## 🛠️ **Technical Highlights**

### **Pure Vanilla JavaScript**

- **Zero dependencies** - runs in any modern browser
- **Lightweight** - single HTML file under 3000 lines
- **Fast rendering** with optimized Canvas API usage
- **Memory efficient** with smart state management

### **One Page Application Architecture**

- **No build process** required
- **Instant loading** - open and start using immediately
- **Self-contained** - all code in one file
- **Progressive enhancement** with graceful fallbacks

### **Advanced Canvas Techniques**

- **Coordinate transformation** for zoom/pan operations
- **Hit detection** for precise mouse interactions
- **Bezier curve mathematics** for smooth link rendering
- **Scale-aware** rendering that maintains quality at all zoom levels

### **Professional UX Patterns**

- **Context-sensitive UI** - panels appear when needed
- **Visual feedback** - clear selection and hover states
- **Keyboard accessibility** - full shortcut support
- **Responsive design** - adapts to any screen size

---

## 🎨 **Screenshots**

### **Clean Interface**

_Minimalist design focuses on your content, not the tools_

### **Node Customization**

_Rich properties panel with real-time preview_

### **Beautiful Connections**

_Smooth bezier curves with customizable control points_

### **History Timeline**

_Visual timeline of all your changes with click-to-jump navigation_

---

## 🚀 **Quick Start**

1. **Download** the `index.html` file
2. **Open** in any modern web browser
3. **Start creating** - no installation required!

```bash
# Clone the repository
git clone https://github.com/yourusername/nodenote.git

# Open in browser
open index.html
```

---

## 💡 **Use Cases & Examples**

### 🧠 **Mind Mapping**

Create visual maps of your thoughts with unlimited space and natural connections.

### 📊 **Project Planning**

Design workflows, map dependencies, and visualize project structures.

### 🎓 **Study Notes**

Connect concepts, create knowledge graphs, and build visual learning aids.

### 💼 **Team Brainstorming**

Collaborate on ideas with shareable exports and clean visual organization.

### 🏗️ **System Design**

Architecture diagrams, data flow visualization, and technical documentation.

---

## 🔧 **Browser Compatibility**

- ✅ **Chrome** 88+ (Recommended)
- ✅ **Firefox** 85+
- ✅ **Safari** 14+
- ✅ **Edge** 88+

**Requirements**: Modern browser with Canvas API and ES6 support

---

## 📝 **Features Checklist**

### **Core Functionality**

- ✅ Infinite canvas with zoom/pan
- ✅ Node creation and editing
- ✅ Link creation with bezier curves
- ✅ Drag and drop interactions
- ✅ Properties panel with real-time updates

### **Customization**

- ✅ Node shapes (rectangle/circle)
- ✅ Font size control (8-24px)
- ✅ Border toggle
- ✅ Circle radius adjustment
- ✅ Link curve customization
- ✅ Arrow direction control

### **Advanced Features**

- ✅ 50-state undo/redo system
- ✅ Visual history panel with navigation
- ✅ Export/import functionality
- ✅ Keyboard shortcuts
- ✅ Selection management
- ✅ Smart state tracking

### **User Experience**

- ✅ Context-sensitive UI
- ✅ Visual feedback and animations
- ✅ Responsive design
- ✅ Accessibility features
- ✅ Performance optimization

---

## 🤝 **Contributing**

NodeNote is built to be easily extensible. Contributions are welcome!

### **Development Setup**

1. Fork the repository
2. Make your changes to `index.html`
3. Test in multiple browsers
4. Submit a pull request

### **Code Style**

- **Vanilla JavaScript** only (no frameworks)
- **ES6+ features** for modern browsers
- **Clear, descriptive** variable and function names
- **Comprehensive comments** for complex logic

---

## 📄 **License**

MIT License - feel free to use NodeNote in your projects!

---

## 🌟 **Why NodeNote?**

### **🚀 Instant Start**

No installation, no setup, no learning curve. Open and start creating immediately.

### **🎯 Purpose-Built**

Designed specifically for visual thinking and idea connection, not generic note-taking.

### **⚡ Lightning Fast**

Pure vanilla JavaScript means instant loading and smooth interactions.

### **🔧 Fully Customizable**

Every aspect can be adjusted to match your thinking style and visual preferences.

### **💾 Your Data, Your Control**

Local-first design with export functionality. Your ideas stay private and portable.

---

**Ready to visualize your ideas?**

[🚀 **Get Started Now**](#quick-start) | [📚 **View Documentation**](#how-to-use) |
[🌟 **Star on GitHub**](https://github.com/yourusername/nodenote)

---

_Built with ❤️ using vanilla JavaScript. No frameworks, no dependencies, just pure web technology._
