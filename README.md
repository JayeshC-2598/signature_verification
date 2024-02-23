# Signature Verification System

Application to detect the similarity of two signatures.

1. This Application helps mathematically evaluate similarity of two signatures. 
2. Simply capture or upload the picture of both signatures to be compared.
3. Both the images will be displayed on the screen that are being compared.
4. The pop-up will show the percentage match of the signatures.
5. The signatures are compared using structural_similarity_index_measure in skimage.metrics package.


## Prerequisites
1. Python >=3.6
2. OpenCV
3. Scipy
4. Scikit-image


## Run
1. `pip install requirements.txt`
2. `python main.py`
