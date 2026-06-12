# 🎵 Interactive Raga Visualizer

> An interactive web application that explores Indian classical ragas through graph theory, set theory, and real-time visualization.

![License](https://img.shields.io/badge/license-MIT-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![HTML5](https://img.shields.io/badge/HTML5-Web-orange)
![CSS3](https://img.shields.io/badge/CSS3-Styling-blue)

---

## 🌟 Project Overview

Indian classical ragas are traditionally understood through their melodic patterns, emotional character, and performance practices. This project approaches ragas from a computational and mathematical perspective.

**Interactive Raga Visualizer** models ragas as mathematical structures and presents them through an intuitive visual interface. By combining concepts from **Graph Theory**, **Set Theory**, **Music Theory**, and **Interactive Data Visualization**, the project enables users to explore how ragas are constructed and how they relate to one another.

The application transforms abstract musical concepts into dynamic visual representations that can be explored, compared, and analyzed interactively.

---

## ✨ Features

### 🎼 Circular Pitch-Class Visualization

Each raga is represented as a circular pitch-class diagram based on the twelve-note chromatic system.

Features include:

* Interactive circular layout
* Highlighted swaras belonging to the selected raga
* Clear visualization of pitch relationships
* Responsive and intuitive design
* Mathematical representation of note collections

The circular representation emphasizes octave equivalence while providing a compact overview of the raga's structure.

---

### 🎹 Real-Time Playback Visualization

Watch the graph come alive as the raga is played.

During playback:

* Active notes illuminate dynamically
* Visual transitions follow musical progression
* Graph nodes respond in real time
* Users can observe how the raga evolves note by note

This feature bridges the gap between sound and structure by allowing users to see music as it unfolds.

---

### 🔍 Mathematical Raga Comparison

Compare two ragas using fundamental set-theoretic operations.

#### Common Notes (Intersection)

Identify notes shared by both ragas.

```text
A ∩ B
```

Useful for discovering structural similarities.

#### Unique Notes (Difference)

Find notes that distinguish one raga from another.

```text
A − B
```

Highlights characteristic swaras and defining features.

#### Combined Note Collection (Union)

View all notes present across both ragas.

```text
A ∪ B
```

Provides a broader picture of the combined pitch space.

---

### 📊 Graph-Theoretic Analysis

Beyond simple note collections, ragas can be interpreted as graphs.

#### Graph Representation

* **Vertices:** Pitch classes (swaras)
* **Edges:** Musical relationships or transitions
* **Subgraphs:** Individual ragas
* **Metrics:** Structural and connectivity analysis

This representation enables computational exploration of musical structure and opens opportunities for deeper musicological research.

---

## 🧠 Mathematical Foundation

The project treats ragas as subsets of a universal pitch-class set.

```text
U = {S, r, R, g, G, m, M, P, d, D, n, N}
```

A raga can then be represented mathematically as:

```text
Raga ⊆ U
```

Example:

```text
Yaman = {S, R, G, M, P, D, N}
```

Using this model, relationships between ragas can be analyzed through standard set operations and graph-theoretic concepts.

---

## 🎯 Applications

### 🎓 Music Education

* Teaching raga structures visually
* Understanding note relationships
* Interactive classroom demonstrations

### 🔬 Computational Musicology

* Formal representation of ragas
* Comparative analysis
* Structural classification studies

### 📈 Data Visualization

* Visual exploration of musical systems
* Interactive graph-based learning
* Educational technology applications

### 🤖 Research and Experimentation

* Pattern discovery
* Similarity analysis
* Mathematical modeling of music

---

## 🛠️ Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6+)

### Visualization

* SVG
* Canvas
* Graph-based rendering techniques

### Audio

* Web Audio API

### Concepts

* Graph Theory
* Set Theory
* Network Analysis
* Computational Musicology

---

## 🚀 Future Enhancements

Planned improvements include:

* 🎵 Aroha–Avaroha visualization
* 🌐 Interactive network of related ragas
* 📊 Similarity scoring and clustering
* 🎹 MIDI support
* 🤖 Machine-learning-based raga recommendations
* 📚 Expanded raga database
* 🎨 Custom visualization themes
* 🔊 Advanced playback analytics

---

## 📸 Example Workflow

1. Select a raga.
2. View its circular pitch-class diagram.
3. Start playback.
4. Observe note activations in real time.
5. Select another raga.
6. Compare them mathematically.
7. Analyze intersections, differences, and structural similarities.

---

## 🌍 Motivation

Music and mathematics share deep structural connections.

This project explores those connections by representing Indian classical ragas as mathematical objects that can be visualized and analyzed computationally. The goal is to make complex musical structures more accessible, intuitive, and engaging for students, musicians, and researchers alike.

---

## 👨‍💻 Author

### Tanay Pant

🎓 Computer Science Enthusiast

🎤 Vocalist

🎼 Passionate about Indian Classical Music

📊 Interested in Graph Theory, Set Theory, and Computational Musicology

💻 Building projects at the intersection of Music, Mathematics, and Technology

---

## 📄 License

This project is licensed under the MIT License.
