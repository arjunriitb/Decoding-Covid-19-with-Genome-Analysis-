# Decoding-Covid-19-with-Genome-Analysis

1. **Load Data**: Load the `cord-ner-full.parquet.gzip` dataset and extract relevant biomedical entities (e.g., genes, proteins).  
2. **Entity Pair Extraction**: Identify relationships between consecutive entities within the same sentence using NLP techniques.  
3. **Build Knowledge Graph**: Use NetworkX to construct a directed graph from the extracted entity pairs.  
4. **Visualization and Analysis**: Visualize the Knowledge Graph to uncover entity interactions and analyze their frequency and relationships.  
5. **Export**: Save the Knowledge Graph in `.gexf` format for further exploration.
