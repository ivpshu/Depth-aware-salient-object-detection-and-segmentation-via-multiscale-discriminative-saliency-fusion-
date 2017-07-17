# Depth-aware-salient-object-detection-and-segmentation-via-multiscale-discriminative-saliency-fusion-

#
% This code is for "[1] H. Song; Z. Liu; H. Du; G. Sun; O. L. Meur; T. Ren, "Depth-aware Salient Object
 Detection and Segmentation via Multiscale Discriminative Saliency Fusion
 and Bootstrap Learning," IEEE Transactions on Image Processing, vol. 26, no. 9, pp. 4204 - 4216, Jun. 2017., and can only be used for non-comercial purpose. 
% If you use our code, please cite [1].
% 
% Code Author: Hangke Song
% Email: hksong0209@163.com
% Date: 2017.07.11
#

How to use:

1. Run .\code_sal\demo.m to learn how to get MDSF sal map.(refer to .\code_sal\train_mat_song\s_train_regressor to train a new RF regressor)

2. Then, run .\code_seg\demo.m to learn how to get object seg result based on sal map.

Note: 
% this version of the code is mainly for testing (may be with chinese comments in some m files), formal version of the code will be released soon.
% The ucm data for region pre-seg can be obtained using code in "ucm_code_linux" for linux.
