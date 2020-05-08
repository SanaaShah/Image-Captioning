# Image Captioning

Generating a description of an image is called image captioning. Image captioning requires to recognize the important objects, their attributes and their relationships in an image. It also needs to generate syntactically and semantically correct sentences. Deep learning-based techniques and machine learning are capable of handling the complexities and challenges of image captioning. 

## Data Visualization and Exploration 
 
The dataset that I have used for this project is Microsoft’s COCO (Common objects in context) dataset. COCO was an initiative to collect natural images, the images that reflect everyday scene and provides contextual information. In everyday scene, multiple objects can be found in the same image and each should be labeled as a different object and segmented properly. COCO dataset provides the labeling and segmentation of the objects in the images. A machine learning practitioner can take advantage of the labeled and segmented images to create a better performing object detection model. Each image in the dataset has a total of five related captions. Here is an example, 
 
 ![COCO Example](/images/coco.JPG)
 
 ## The Results
 The model was tested on the test images from the COCO dataset. The images are first loaded with the help of the data loader. Then they are pre-processed and passed through the encoder and decoder. Finally, in the end the images are passed through the model and the following results were obtained. Below are the examples of some of the output. 
 
 ![Sample Output](/images/output.JPG)
 
 ### Please note that if you want to read the complete documentation and want to know how this project works, open the [report.pdf](https://github.com/SanaaShah/Image-Captioning/blob/master/report.pdf) file in this repository.
 
