# CNN transfer learning and architecture design for landmark classification and tagging for social media

In this project, we will apply Convolutional Neural Network (CNN) to build a landmark classifier.

Photo sharing and photo storage services like to have location data for each photo that is uploaded. With the location data, these services can build advanced features, such as automatic suggestion of relevant tags or automatic photo organization, which help provide a compelling user experience. Although a photo's location can often be obtained by looking at the photo's metadata, many photos uploaded to these services will not have location metadata available. This can happen when, for example, the camera capturing the picture does not have GPS or if a photo's metadata is scrubbed due to privacy concerns.

If no location metadata for an image is available, one way to infer the location is to detect and classify a discernible landmark in the image. Given the large number of landmarks across the world and the immense volume of images that are uploaded to photo sharing services, using human judgement to classify these landmarks would not be feasible.

In this project, we will take the first steps towards addressing this problem by building models to automatically predict the location of the image based on any landmarks depicted in the image. We will go through the machine learning design process end-to-end: performing data preprocessing, designing and training CNNs, comparing the accuracy of different CNNs, and using our own images to heuristically evaluate our best CNN.

## Project Steps
The high level steps of the project include:

* Create a CNN to Classify Landmarks (from Scratch) - Here, we'll visualize the dataset, process it for training, and then build a convolutional neural network from scratch to classify the landmarks. We'll also describe some of our decisions around data processing and how we chose our network architecture.

* Create a CNN to Classify Landmarks (using Transfer Learning) - Next, we'll investigate different pre-trained models and decide on one to use for this classification task. Along with training and testing this transfer-learned network, we'll explain how we arrived at the pre-trained network we chose.

* Write Our Landmark Prediction Algorithm - Finally, we will use our best model to create a simple interface for others to be able to use our model to find the most likely landmarks depicted in an image. We'll also test out our model ourselves and reflect on the strengths and weaknesses of our model.
