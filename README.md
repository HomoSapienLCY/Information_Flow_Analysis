# Description:
The matlab and CUDA implementation of a O(n^2m) information flow analysis algorithm (http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000350)
This project is a part of a project at http://wanglab.ucsd.edu/ , you are welcome to contact chl556@ucsd.edu if you have any questions.

# Time Test:
A network with N (number of nodes) = 3,447 and M (number of edges) = 92,026

| Algorithm | Runtime (s) | Speed Compared to Original |
| ----------- | ------------ | -------------- | 
| Original Algorithm (CPU, 4 cores)      | 20976.2      | 1.00x  |
| New Algorithm (CPU, 4 cores)       | 9433.4       | 2.22x |
| New Algorithm (GPU, GTX580x1)           | 1205.8       | 17.40x |

