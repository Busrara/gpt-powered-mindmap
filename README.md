# Visualizing Knowledge Graphs from Text

## Overview
This is a Python tool for creating knowledge graphs and visual mind maps using GPT-4. It takes concepts and relationships from text and shows them as a graph by NetworkX and Matplotlib.

## Features
- **Named Entity Recognition (NER)**: Uses a pretrained BERT-based model (`dslim/bert-base-NER`) from Hugging Face to recognize entities like people, locations, organizations, and more from text.
- **Relationship Mapping**: Automatically creates relationships between the recognized entities and categorizes them into domains (e.g., `Artificial Intelligence`, `Machine Learning`).
- **Graph Visualization**: Uses `networkx` and `matplotlib` to give a visual representation of the knowledge grap. It demonstrates how the entities are connected.

## Installation
To install and use this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Busrara/knowledge-graph-ner.git
   cd MindMapGPT

