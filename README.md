# 🎵 Interactive Raga Visualizer

### Graph-Theoretic and Set-Theoretic Exploration of Hindustani Classical Ragas

> An interactive web application that models Hindustani classical ragas as mathematical structures using pitch-class sets, directed graphs, similarity metrics, and data visualization.

---

## 🌟 Overview

**Interactive Raga Visualizer** is a computational musicology project that explores the relationship between Indian classical music and mathematics.

The application represents Hindustani ragas as **pitch-class sets**, **directed graphs**, and **visual networks**, allowing users to examine their structure through the lens of graph theory and set theory. Rather than viewing a raga solely as a musical scale, the project treats it as a mathematical object whose properties can be visualized, compared, and analyzed interactively.

Built entirely with **HTML, CSS, JavaScript, and D3.js**, the project runs directly in the browser without requiring a backend or external database.

---

## 🎯 Objectives

This project aims to:

* Visualize ragas as mathematical structures
* Demonstrate applications of graph theory in music
* Explore set-theoretic relationships between ragas
* Provide an educational tool for learning Hindustani music theory
* Bridge the fields of music, mathematics, and computer science

---

# ✨ Features

## 🎼 Raga Explorer

Explore individual ragas through interactive visual representations.

### Circular Pitch-Class Diagram

Every raga is displayed on a circular arrangement of the twelve pitch classes:

```text
S • r • R • g • G • M • m • P • d • D • n • N
```

Features include:

* Highlighted notes belonging to the selected raga
* Special emphasis on Vadi and Samvadi swaras
* Visualization of forbidden notes
* Interactive tooltips
* Ascending (Aaroh) and descending (Avaroh) pathways
* Optional note playback using Tone.js

This representation emphasizes octave equivalence while making note relationships immediately visible.

---

### Directed Note Graph

Each raga is also represented as a directed graph.

#### Graph Components

* **Nodes** represent swaras (notes)
* **Edges** represent melodic transitions
* **Directed arrows** show movement between notes
* **Highlighted nodes** indicate Vadi and Samvadi

The graph reveals structural patterns that are difficult to observe in traditional notation.

---

### Metadata Dashboard

For every raga, the application displays:

* Parent Thaat
* Vadi and Samvadi
* Time of performance
* Emotional mood (*Rasa*)
* Number of notes used
* Similarity score relative to the previously viewed raga

---

## 🔍 Raga Comparison

Compare two ragas side-by-side using mathematical operations.

### Set-Theoretic Analysis

Each raga is represented as a subset of the universal pitch-class set:

```text
U = {S, r, R, g, G, M, m, P, d, D, n, N}
```

The comparison view computes:

### ∩ Intersection

Notes shared by both ragas.

### ∪ Union

Combined note collection of both ragas.

### − Difference

Notes unique to each raga.

### Similarity Score

Similarity is measured using the **Jaccard Index**:

```text
J(A,B) = |A ∩ B| / |A ∪ B|
```

where:

* A = note set of Raga A
* B = note set of Raga B

The result provides a quantitative measure of how closely related two ragas are.

---

### Interactive Venn Diagram

The comparison interface includes a Venn-style visualization displaying:

* Notes unique to Raga A
* Notes unique to Raga B
* Shared notes between both ragas

Alongside numerical metrics and explanatory interpretations.

---

## 🌐 Thaat Map

Explore the foundational framework of Hindustani classical music through the ten canonical thaats.

### Included Thaats

* Kalyan
* Bilawal
* Khamaj
* Kafi
* Asavari
* Bhairavi
* Bhairav
* Poorvi
* Marwa
* Todi

Each thaat card displays:

* Constituent notes
* Komal swaras
* Shuddha swaras
* Teevra swaras
* Number of associated ragas in the dataset

---

### Similarity Heatmap

A full similarity matrix compares every thaat against every other thaat.

Features:

* Color-coded similarity scores
* Hover tooltips
* Shared-note analysis
* Visual identification of related thaats

This provides a high-level view of the structural relationships within the Hindustani music system.

---

# 🧠 Mathematical Foundation

The project combines several mathematical ideas.

## Set Theory

A raga is modeled as a subset of the universal note collection.

Example:

```text
Yaman = {S, R, G, m, P, D, N}
```

Operations such as intersection, union, and difference enable rigorous comparison between ragas.

---

## Graph Theory

A raga can also be interpreted as a graph:

* Vertices → Notes
* Edges → Melodic transitions
* Degree → Connectivity
* Centrality → Relative importance of notes

The concept of **Vadi** naturally aligns with graph centrality, as it often functions as a structurally significant node within the musical network.

---

## Similarity Metrics

The application uses the Jaccard Index to quantify overlap between note sets.

This allows subjective musical similarity to be supplemented with objective mathematical analysis.

---

# 📚 Dataset

The project includes representative ragas from major Hindustani traditions:

* Yaman
* Bhairav
* Kafi
* Bhupali
* Bhairavi
* Bageshri
* Darbari
* Hamsadhwani
* Malkuns
* Todi

Each raga contains:

* Parent Thaat
* Note collection
* Aaroh
* Avaroh
* Vadi
* Samvadi
* Performance time
* Mood descriptor
* Forbidden notes

All data is stored directly within the application.

---

# 🛠️ Technology Stack

### Frontend

* HTML5
* CSS3
* Vanilla JavaScript

### Visualization

* D3.js v7
* SVG Rendering
* Interactive Graph Layouts

### Audio

* Tone.js (Optional)

### Concepts

* Graph Theory
* Set Theory
* Data Visualization
* Computational Musicology

---

# 🚀 Future Improvements

Planned enhancements include:

* Additional ragas and thaats
* Graph centrality analytics
* Community detection and clustering
* Interactive melodic phrase visualization
* MIDI support
* Raga recommendation engine
* Exportable graph datasets
* Machine-learning-based similarity analysis

---

# 🎓 Educational Value

This project demonstrates how computational methods can be applied to artistic and cultural systems.

It serves as:

* A music education tool
* A graph theory visualization project
* A set theory application
* A computational musicology experiment
* A data visualization case study

---

# 👨‍💻 Author

## Tanay Pant

🎓 Computer Science Enthusiast

🎤 Vocalist

🎼 Passionate about Hindustani Classical Music

📊 Interested in Graph Theory, Set Theory, Data Visualization, and Computational Musicology

💻 Building projects at the intersection of Music, Mathematics, and Technology

---

# 📄 License

This project is licensed under the MIT License.

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
