# -Hierarchical-Model-based-Motion-estimation-ECCV-1992-paper-implementation
This repository is an implementation of the paper "Hierarchical Model-Based Motion Estimation" which was published in ECCV'1992. In this paper, Bergen, James R., et al. had introduced three parametric models and 1 non-parametric model for the optical flow estimation between two images. 

Parametric Models:
1. Affine Flow
2. Planar Flow
3. Rigid Flow (NOT IMPLEMENTED)

Non-Parametric Model:
1. General Flow

CODES:
THREE MODELS' CODES ARE PLACED IN THREE SEPARATE ipynb FILES.

IN ORDER TO RUN ANY ONE OF THE MODELS:

1. OPEN THE CORRESPONDING ipynb FILE

2. MOVE TO THE PART WHERE "RUN THE CODE FROM HERE" IS WRITTEN

3. ENTER THE PATH OF THE IMAGE 1 AND IMAGE 2 FILES 

4. RUN THE CODE ACCORDING TO THE COMMENTS WRITTEN.  


FOR THE AFFINE AND PLANAR FLOW MODELS, WE HAVE USED 2 TYPES OF INPUTS NAMELY LAPLACIAN PYRAMIDS (AS EXPLAINED IN THE PAPER) AND GAUSSIAN PYRAMIDS.

RESULTS ARE PRESENT IN THE CORRESPONDING FOLDERS. 

The commented code and the dataset used have been provided. The project was implemented in python 3.6.8.

References:
[1] Bergen, James R., Patrick Anandan, Keith J. Hanna, and Rajesh Hingorani. "Hierarchical model-based motion estimation." In European conference on computer vision, pp. 237-252. Springer, Berlin, Heidelberg, 1992.
[2] Hanna, K. J. "Direct multi-resolution estimation of ego-motion and structure from motion." In Proceedings of the IEEE workshop on visual motion, pp. 156-157. IEEE Computer Society, 1991.
