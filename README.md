# nfl-big-data-bowl-2020
This repository host different approaches developed to solve the challenge proposed in the Big Data Bowl 2020.

[Winner Solution](1st_place_zoo_solution_v2.ipynb.ipynb): reproduces the 1st place winner solution of the NFL Big Data Bowl 2020 kaggle competition.
[Winner Solution - Pytorch](pytorch_version.ipynb.ipynb): implementation of the NFL Big Data Bowl 2020 winner solution using graph neural networks (torch geometric)

[Player Influence Area - CNN](my_solution.ipynb): exploits the idea of player influence area proposed in "Wide Open Spaces: A statistical technique for measuring space creation in professional soccer". The idea is to feed a CNN with an array of 22 images, where each image represents the influence area of each player.

[Graph Convolutional Network](nfl_graph_neural_networks_v1.ipynb): represents the traking data using a graph G(V, E), where V is the set of nodes, and E the set of edges. It only considers the rusher against the defensive team in the representation of the data.
