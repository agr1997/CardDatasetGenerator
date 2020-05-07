Credits to https://github.com/geaxgx/playing-card-detection for the idea and methodology.

This is an unclean Python notebook that I used to generate a dataset of 100,000+ labelled images of playing cards which can be used
to train an object detection model: https://github.com/agr1997/card_dataset

Once the dataset was generated, I converted the images to XML format (provided by YOLO authors) so that it is compatible with YOLOv3. 
After retraining, I obtained a model with accuracy over 99.6+ accuracy on the dataset. 

Attached is a video showing the results. 
