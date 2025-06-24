Lacunarity curve

The lacunarity can be understood as the deviation of a fractal from translational invariance, and translational invariance can also be a characteristic of nonfractal structures. 
Furthermore, translational invariance is scale dependent, since structures that are heterogeneous at small scales may be quite homogeneous when examined at larger scales or vice versa, 
hence the importance of a multiscale measure such as lacunarity. A high lacunarity suggests an irregular distribution of gaps, implying structural dispersion.

In this context, taking as input data the pixel matrix in "txt format", this code calculates the lacunarity curve and the lacunarity exponent through the "Gliding Box" algorithm. 
The pixel matrix can come from any type of digital image or microscopy. The "L" parameter is the dimension of the matrix and must be indicated by an integer. 
The "threshold" parameter depends on the characteristics of the data and can be obtained externally using some automated method such as the OTSU algorithm or 
Artificial Intelligence, however, we suggest as default the average of the pixel matrix data. The "m" parameter represents the values of the box size, 
which can be a sequence of integers "m = 1,2,4,8,16,32,64,128". This sequence can be changed and extended to receive other values as long as the "lacunarity" function is adjusted for this. 
A test matrix (surf.txt) for evaluating the code is also provided.

The output data are: Lacunarity curve (lacunarity L(m) versus box size m on log-log scale), Lacunarity Exponent (slope of the lacunarity curve fit) and R-squared of the lacunarity curve fit.

Below we show the results panel in the R-studio interpreter:

![Results_Panel](https://github.com/user-attachments/assets/4c8c1af2-a000-4dd8-bcd5-69cfe6b85e00)
