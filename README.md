# Image-similarity
This will help to compare two images if they are similar to each other or not
Two images are loaded in image1 and image2. image1 loads reference image and image2 holds...
...the image to be comapred in similarity.
A VGG16 network is used without classifier i.e. in feature extractor mode to extract features
from both the images.
The extracted feature vectors stored in features1 and features2 are then used for image similarity
comparision.
Cosine Similarity is used for comapring two feature vectors from two images.
The final output prints the score of cosine similarity in the range [0,1]. The closer
value to 0 indictaes very dissimilar images while values closer to 1 indicate similar images.
The output also results in pearson correlation coefficient and p-value for showing how much 
non-corelated the feature vectors are.
The output also shows three plots: First two plots show feature vectors and the third plot..
..show scattter plot between two feature vectors alon the two axes.

