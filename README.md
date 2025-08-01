# Hierarchical-Object-Detection-with-YOLOv8-and-GNNs

![System Architecture](docs/architecture_diagram.png)

This repository implements a hierarchical object detection system combining YOLOv8's real-time detection capabilities with Graph Neural Networks (GNNs) for semantic reasoning, as described in the dissertation "Hierarchical Object Detection" from the University of Stirling.

## Key Features

- **Hierarchical Classification**: Predicts objects at multiple abstraction levels (e.g., Animal → Dog → Labrador)
- **Graph Neural Networks**: Models label dependencies using WordNet taxonomy
- **Real-Time Performance**: Maintains YOLOv8's speed while adding hierarchical reasoning
- **Novel Evaluation Metrics**: Implements hierarchical precision/recall and tree edit distance

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Awais-khanBangash/Hierarchical-Object-Detection-with-YOLOv8-and-GNNs
   cd hierarchical-object-detection
