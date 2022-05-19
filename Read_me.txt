In this repository we have several files like input.pickel, graph.py, vne.py and such files which contains codes interlinked with each other.

1. graph.py: This file is used to generate the graph. To generate the graph we have to specify some parameters such as minimum number of              node, maximum number of nodes, minimum node weights, maximum node weights, minimum edge weights, maximum edge weights and               other parameters as well.

2. graph_Extract.py: This file is used to extract graph which is being used to design substrate graph and VN Request.

3. VNE.py: This file is used to create virtual Network Request.

4. ReadPickel.py: This file is use to read the pickel files.

5. input.pickel: This is an pickel file which is used to generate input graph(Physical server).

6. ProjFile.ipynb: This is the main file which contains Node and Link Mapping.

7. P3_ALIB_MASTER folder: This folder contain pickel files.

Input:
1. Graph repersentation of the substrate network.
2. K number of VNRequest.

Output:
Embedded Mapping of all VNRequest.

Steps to run:

1. Create a folder in google drive and upload all the files which is present in this zipped folder.

2. To execute the code we have to just run the "projFile.py" file in google colab. 

3. set the path in the code before execution.

4. Run each block of code one by one. It will automatically generate the Substrate and Virtual Network.

5. Please make a note. In this code we have used our predefine substrate graph, name as "demo_substrate", which is an 8x8 complete graph or another graph is also availabe to use, name as "substrate" which contains 84 node (which we avoided to use due to complex structure). Analysing small graph is easier, faster and well representable. Output of this file gives Node and Link Mapping for Virtual Node Requests (VNR).






