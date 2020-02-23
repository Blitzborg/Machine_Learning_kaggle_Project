# Recognizing Families In the Wild (RFIW): Data


Competition is based on the Families In the Wild (FIW) dataset. See project page for more information, https://web.northeastern.edu/smilelab/fiw/.

Contents are as follows:
* **test-public-face**
    * Directories of faces to train (and validate) with. Faces are split by family ID, then into respective family-member ID.<sup>1</sup>
* **test-public-lists**
    * Pair lists made up of 3 columns (i.e., pair per row):<sup>2</sup>
        1. label (i.e., 1/0 aka KIN/ NON-KIN)
        2. path to face for subject 1
        3. path to face for subject 2
* **test-private-face**
    * Faces for testing (i.e., blind, so faces are all in single folder named face[0-N] where N is the number of test faces.)
* **test-private-lists**
    *  Pair lists made up of 2 columns: 
        1. image name for subject 1 
        2. image name for subject 2. 
* **test-private-labels**
    *  Ground truth for test set, using same name scheme and order as respective lists.           

Various scripts and benchmarks are available on Github, https://github.com/visionjo/FIW_KRT. Soon these will be moved over to Kaggle as Kernels.

<sup>1</sup> See README in Github repo for more information about the contents of *test-public-faces*.

<sup>2</sup> Note that the order is set in accordance with the name of file (e.g., fd has father in column 2 and daughter in column 3)


*Author: Joseph Robinson* <br>
*Email: robinson.jo@husky.neu.edu* <br>
*Web: www.jrobsvision.com*
