# 🎵 Interactive Raga Visualizer

### Visualizing Hindustani Classical Ragas Through Graph Theory and Set Theory

An interactive single-file web application that explores Hindustani classical ragas using mathematical and visual representations. The project models ragas as pitch-class sets and directed graphs, enabling users to study their structure, compare note collections, and examine relationships between thaats through interactive visualizations.

---

## 📖 Overview

Indian classical ragas are traditionally understood through their swaras, melodic movements, and performance practices. This project presents an alternative perspective by representing ragas as mathematical structures that can be visualized and analyzed.

The application combines concepts from:

* 🎼 Hindustani Music Theory
* 🕸️ Graph Theory
* 📐 Set Theory
* 📊 Data Visualization

to create an interactive environment for exploring how ragas are constructed and how they relate to one another.

The entire project is contained within a single HTML file and runs directly in the browser.

---

# ✨ Features

## 🎼 Raga Explorer

Explore individual ragas through interactive visual representations.

### Circular Pitch-Class Diagram

Each raga is displayed on a circular arrangement of the twelve pitch classes:

```text
S • r • R • g • G • M • m • P • d • D • n • N
```

The visualization highlights:

* Notes used in the selected raga
* Vadi (primary note)
* Samvadi (secondary note)
* Forbidden notes
* Unused notes
* Aaroh (ascending sequence)
* Avaroh (descending sequence)

Interactive tooltips provide additional information about each note and its role within the raga.

---

### Directed Graph Representation

Each raga is also represented as a directed graph.

In this representation:

* Nodes represent swaras (notes)
* Directed edges represent note transitions
* Aaroh and Avaroh pathways are displayed separately
* Vadi and Samvadi notes receive visual emphasis

This view helps illustrate the structural movement of a raga beyond a simple note collection.

---

### Metadata Panel

For every raga, the application displays:

* Raga name
* Parent thaat
* Vadi and samvadi
* Time of performance
* Mood (rasa)
* Number of notes used
* Similarity score relative to the previously viewed raga

---

# 🔍 Raga Comparison

Compare two ragas side by side using set-theoretic concepts.

### Dual Visualization

The comparison view displays:

* Two pitch-class diagrams
* Shared notes
* Unique notes
* Similarity statistics

---

### Set Operations

Each raga is treated as a set of notes.

The application computes:

#### Intersection

Notes shared by both ragas.

```text
A ∩ B
```

#### Difference

Notes unique to a specific raga.

```text
A − B
```

#### Union

Combined note collection.

```text
A ∪ B
```

---

### Venn Diagram Comparison

A Venn-style visualization shows:

* Notes unique to Raga A
* Notes shared by both ragas
* Notes unique to Raga B

Additional statistics include:

* Shared-note count
* Similarity percentage
* Notes unique to each raga

---

### Jaccard Similarity

Similarity is measured using the Jaccard Index:

```text
Similarity = |A ∩ B| / |A ∪ B|
```

This metric quantifies the overlap between two ragas based on their note collections.

---

# 🌐 Thaat Map

Explore relationships between the ten canonical Hindustani thaats.

The application includes:

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

---

### Thaat Cards

Each thaat card displays:

* Thaat name
* Constituent notes
* Komal notes
* Shuddha notes
* Teevra notes
* Number of ragas represented in the dataset

---

### Similarity Heatmap

A 10 × 10 comparison matrix visualizes similarity between all thaats.

Features include:

* Color-coded similarity values
* Hover interactions
* Shared-note information
* Comparative analysis across the Hindustani thaat system

---

# 🧮 Mathematical Concepts

## Pitch-Class Sets

Each raga can be represented as a subset of the twelve-note pitch-class universe.

Example:

```text
Yaman = {S, R, G, m, P, D, N}
```

---

## Set Theory

The project uses:

* Union
* Intersection
* Difference

to compare ragas and identify shared musical structure.

---

## Graph Theory

Ragas are modeled as directed graphs where:

* Vertices represent notes
* Edges represent melodic transitions

This representation captures relationships between notes in Aaroh and Avaroh sequences.

---

## Similarity Metrics

The Jaccard Index is used to measure similarity between:

* Two ragas
* Two thaats

based on the overlap of their note sets.

---

# 📚 Dataset

The project includes the following ragas:

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

along with all ten canonical Hindustani thaats.

All data is hardcoded within the application.

---

# 🛠️ Technologies Used

* HTML5
* Embedded CSS
* Embedded JavaScript
* D3.js (Visualization Library)

### Architecture

* Single self-contained HTML file
* No backend
* No database
* No build tools
* No installation required

Simply open the HTML file in a modern browser to run the application.

---

# 🎯 Educational Purpose

This project demonstrates how concepts from mathematics and computer science can be applied to musical systems.

It serves as:

* A visualization tool for Hindustani classical music
* A practical application of graph theory
* A demonstration of set-theoretic analysis
* An educational resource for understanding raga structure

---

# 👨‍💻 Author

### Tanay Pant

🎓 Computer Science Enthusiast

🎤 Vocalist

🎼 Interested in Hindustani Classical Music

📊 Exploring the intersection of Mathematics, Music, and Interactive Visualization

---

# 📄 License

MIT License
