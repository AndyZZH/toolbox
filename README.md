Documentation: https://pdollar.github.io/toolbox/



Introduction:

  This toolbox is meant to facilitate the manipulation of images and video in Matlab. Its purpose is to complement, not replace, Matlab's Image Processing Toolbox, and in fact it requires that the Matlab Image Toolbox be installed. Emphasis has been placed on code efficiency and code reuse.

description:
  1. The toolbox is divided into 7 parts, arranged by directory:
     channels, classify, detector, filters, images, matlab, videos
     
  2. This code is licensed under the Simplified BSD License.
  
  3. Installation by the Matlab path:
     >> addpath(genpath('path/to/toolbox/')); savepath;
     run the compile script for the mex files: 
     >> toolboxCompile;
     
  4. Citation:
     @misc{PMT, 
     author = {Piotr Doll\'ar}, 
     title = {{P}iotr's {C}omputer {V}ision {M}atlab {T}oolbox ({PMT})}, 
     howpublished = {\url{https://github.com/pdollar/toolbox}} 
     } 
