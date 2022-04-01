# CoFSM
The paper has been published in the IEEE TIP journal
Citation Format：
      Yao, Y., Zhang, Y., Wan, Y., Liu, X., Yan, X., & Li, J. (2022). Multi-modal Remote Sensing Image Matching Considering Co-occurrence Filter. IEEE Transactions on Image Processing. vol.31, pp.2584-2597.

Journal Network Links：https://ieeexplore.ieee.org/document/9733789

# Introduction
   Traditional image feature matching methods cannot obtain satisfactory results for multi-model remote sensing images (MRSIs) in most cases because different imaging mechanisms bring significant nonlinear radiation distortion differences (NRDs) and complicated geometric distortion. The key to MRSI matching is trying to weak or eliminating the NRD and extract more edge features. This paper introduces a new robust MRSI matching method based on co-occurrence filter (CoF) space matching, space matching CoFSM. Our algorithm has three steps: (1) a new co-occurrence scale space based on CoF is constructed, and the feature points in the new scale space are extracted by the optimized image gradient; (2) the gradient location and orientation histogram algorithm is used to construct a 152-dimensional log-polar descriptor, which makes the multi-modal image description more robust; and (3) a position-optimized Euclidean distance function is established, which is used to calculate the displacement error of the feature points in the horizontal and vertical directions to optimize the matching distance function. The optimization results then are rematched, and the outliers are eliminated using a fast sample consensus algorithm. Our proposed CoFSM method achieved good effectiveness and robustness.
   
# Others

More details, please look :https://skyearth.org/publication/project/CoFSM/  
 
