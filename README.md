# 📊 Data Structure Visualizer

An interactive, animated web-based tool to visualize and learn **Linear and Non-Linear Data Structures** with step-by-step operations and explanations.

---

## 🌐 Live Demo

Open `ds.html` directly in any browser — no installation required!

---

## ✨ Features

- 🎨 **Lavender Glassmorphism UI** with glitter particle animations
- 📊 **Linear Data Structures** — Array, Stack, Queue, Linked List
- 🌳 **Non-Linear Data Structures** — BST Tree, Max Heap, Graph
- ⚙️ **DS-Specific Operations** for each data structure
- 📝 **Step-by-step Explanation Panel** after every operation
- ⏱️ **Time Complexity Table** for every DS
- 🔁 **Smooth Animations** — push/pop, enqueue/dequeue, node insert/delete
- 📱 **Responsive Design** — works on desktop and mobile

---

## 🗂️ Data Structures & Operations

### 📦 Array
| Operation | Description | Complexity |
|-----------|-------------|------------|
| Insert at End | Append value to last index | O(1) |
| Insert at Index | Insert at specific position | O(n) |
| Delete by Value | Find and remove element | O(n) |
| Search | Linear scan for value | O(n) |
| Traverse / Display | Print all elements | O(n) |

---

### 📚 Stack (LIFO)
| Operation | Description | Complexity |
|-----------|-------------|------------|
| Push | Add element to TOP | O(1) |
| Pop | Remove TOP element | O(1) |
| Peek / Top | View TOP without removing | O(1) |
| isEmpty | Check if stack is empty | O(1) |
| Display | Show TOP to BOTTOM | O(n) |

---

### 🚶 Queue (FIFO)
| Operation | Description | Complexity |
|-----------|-------------|------------|
| Enqueue | Add element at REAR | O(1) |
| Dequeue | Remove element from FRONT | O(1) |
| Front | View FRONT element | O(1) |
| Rear | View REAR element | O(1) |
| isEmpty | Check if queue is empty | O(1) |
| Display | Show FRONT to REAR | O(n) |

---

### 🔗 Linked List
| Operation | Description | Complexity |
|-----------|-------------|------------|
| Insert at Head | Add node at beginning | O(1) |
| Insert at Tail | Add node at end | O(n) |
| Insert at Position | Add node at given position | O(n) |
| Delete by Value | Remove node, relink pointers | O(n) |
| Search | Traverse to find value | O(n) |
| Traverse / Display | Visit all nodes HEAD→NULL | O(n) |

---

### 🌳 Tree (BST — Binary Search Tree)
| Operation | Description | Complexity |
|-----------|-------------|------------|
| Insert | Insert using BST property | O(log n) avg |
| Delete | Remove node (3 cases handled) | O(log n) avg |
| Search | Find value using BST rule | O(log n) avg |
| In-order (L→N→R) | Gives sorted output | O(n) |
| Pre-order (N→L→R) | Root visited first | O(n) |
| Post-order (L→R→N) | Root visited last | O(n) |

---

### ⛰ Heap (Max Heap)
| Operation | Description | Complexity |
|-----------|-------------|------------|
| Insert | Add + Heapify-Up | O(log n) |
| Extract Max | Remove root + Heapify-Down | O(log n) |
| Peek Max | View root (MAX) | O(1) |
| Search | Linear scan | O(n) |
| Display | Show array representation | O(n) |

---

### 🕸 Graph (Undirected)
| Operation | Description | Complexity |
|-----------|-------------|------------|
| Add Vertex | Create new vertex | O(1) |
| Add Edge | Connect two vertices | O(1) |
| Remove Vertex | Delete vertex + all edges | O(V+E) |
| Search Vertex | Find vertex in graph | O(V) |
| BFS Traversal | Level-by-level using Queue | O(V+E) |
| DFS Traversal | Depth-first using Recursion | O(V+E) |
| Adjacency List | Display neighbor list | O(V+E) |

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/anu-x19/data-structure-visualizer.git
   ```
2. Open `ds.html` in your browser
3. Select **Linear** or **Non-Linear** category
4. Choose a Data Structure from the sidebar
5. Enter a value and click any operation card
6. Watch the animation and read the explanation panel!

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure |
| CSS3 | Lavender theme, glassmorphism, animations |
| Vanilla JavaScript | DS logic, SVG rendering, step animations |
| SVG | Tree, Heap, Graph visualization |

> No frameworks. No libraries. Pure HTML + CSS + JS — single file!

---

## 📁 Project Structure

```
data-structure-visualizer/
│
└── ds.html          # Complete visualizer — single file
```

---

## 👩‍💻 Author

**Anu Sri Vaddi**  
B.Tech AI/ML — BVCITS, Andhra Pradesh  
GitHub: [@anu-x19](https://github.com/anu-x19)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
