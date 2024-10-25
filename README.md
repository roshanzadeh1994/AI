# SemArt Project

This project, developed for INFM2100 - Aktuelle Themen der Softwareentwicklung, is a visual art similarity search application. It leverages deep learning models and vector embeddings to identify and retrieve visually similar artworks from a dataset. The code relies on `Milvus` for storing and querying embeddings and `ResNet-50` as a feature extractor model.




## Project Description

The **SemArt Project** enables the analysis and search for artworks with similar visual attributes. By using pre-trained neural networks (ResNet-50) for feature extraction and Milvus for vector similarity search, it can recommend artworks based on visual features, type, and school (e.g., religious, portrait).

### Key Features

- **Image Preprocessing**: Uses `opencv` and `PIL` for image processing.
- **Embeddings**: Creates embeddings using ResNet-50 from the `transformers` library.
- **Vector Database**: Manages embeddings in Milvus, a high-performance vector database.
- **Similarity Search**: Searches similar images based on predefined type and school categories.

## Requirements

- Python 3.9+
- **Libraries**:
  - `transformers`: for feature extraction
  - `numpy`, `pandas`: data handling and analysis
  - `Milvus`: vector database for embedding storage and similarity search
  - `plotly`, `matplotlib`: visualization tools for data analysis
  - `opencv`, `PIL`: image processing


