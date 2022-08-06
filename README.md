# generative_python_music

You can use this script to sonify an undirected graph.
Each voice corresponds to a sorting of the vertices and the corresponding adjacency matrix row. The bitstring of the adjacency matrix is converted to 
integer composition of 8 (for example parameter "by=8" in the code) and is responsible for the durations of this voice. 
The pitches and volumes are created with the k-nearest neighbor algorithm and zipped with the durations. 
I used this script to create an 8-voice piano based piece for relax and study (The random graph used is RandomBarabasiAlbert ):

https://www.youtube.com/watch?v=Uc7D3Q_6baU

Blue Water: https://www.youtube.com/watch?v=vf6ep4M2NJM
