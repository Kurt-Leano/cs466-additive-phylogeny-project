# Additive Phylogeny

This repository consists of a Google Colab notebook that runs the additive phylogeny algorithm utilizing degenerate triples in order to create a distance-based phylogeny consistent with a distance matrix. The graph is drawn using NetworkX for easy visualization of the phylogeny.

## Instructions
Download the Jupyter notebook and open in Google Colab. Select 'Runtime' and click 'Run all.'

## Running
To generate algorithm on other distance matrices:
- Create an n x n dict of dicts, D
- Run additive_phylogeny() on distance matrix D
- Run draw_graph() on returned graph G
