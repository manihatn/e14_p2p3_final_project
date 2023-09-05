# e14_p2p3_final_project
Path to Programmable 3 Final project. Object Detection and Localisation on ultra96v2 using AI/ML

Details about the project can be found below
https://community.element14.com/challenges-projects/design-challenges/pathprogrammable3/b/blog/posts/p2p3---final-blog---object-detection-and-localisation-on-ultra96v2-using-ai-ml

The source code is based on the https://github.com/kaneelgit/ML-DL-Algorithms/blob/main/Object%20Detection%20and%20Localization%20using%20Tensorflow.ipynb

I had to modify:

a. Update the plot_model import module
#from tensorflow.python.keras.utils.vis_utils import plot_model
from tensorflow.keras.utils import plot_model

b. the image location and path was changed to run on google collab.
