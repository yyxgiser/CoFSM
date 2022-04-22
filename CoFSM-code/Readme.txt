                                                                   CoFSM code
Paper: "CoFSM:Multi-modal Remote Sensing Image Matching Considering Co-occurrence Filter"
Code:

Yao, Y., Zhang, Y., Wan, Y., Liu, X., Yan, X., & Li, J. (2022). Multi-modal Remote Sensing Image Matching Considering Co-occurrence Filter. IEEE Transactions on Image Processing. vol.31, pp.2584-2597.

The code is closed under the matlab r2018a version.
     “CoFSM_main.m”are an executable program.
    (1) If you have already installed matlab, please run CoFSM_main.m according to the following instructions.
      >> Parameters setting
	>> The 1 line is the path of the reference image;(Custom path)
	>> The 2 line is the path of the Image to be matched;(Custom path)
	>> The 3 line is the initial window of co-occurrence filtering;(The default is 5)
	>> The 4 line is the number of scale space layers; (The default is 4)
	>> The 5 line is the feature point extraction threshold;  (The default is 1300)

	>>Running 'CoFSM_main.m'

Images datasets:
           It contains 6 multi-modal data types:
       	1-->optical-optical include 1 sets of images;
       	2-->infrared-optical include 1 sets of images;
       	3-->depth-optical include 1 sets of images;
       	4-->map-optical include 1 sets of images;
       	5-->SAR-optical include 1 sets of images;
      	6-->night-day include 1 sets of images.

   For more details of images datasets see the website link: https://ieee-dataport.org/documents/cofsm
   See website link for more details of Code: https://skyearth.org/publication/project/CoFSM/
  Author's Github link: https://github.com/yyxgiser/CoFSM