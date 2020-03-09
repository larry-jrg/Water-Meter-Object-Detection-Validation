# Validation images from first successfully trained model of YOLOv3.  

These images are a 10% subset of images used to train the model.  The model was trained with 30+ images that were 
copied and rotated in 15-degree increments around the full 36 degrees, resulting in over 760 images.  The images were 
selected from a larger set of images taken at random from both the office and field prototypes so that each meter type
was fairly represented during training.  The digit window was inspected so that digits did not dwell on the same values
in the same positions.

The validation was 100% successful.  All intended objects were correctly identified in each image and no extraneous objects
were marked.  Both meter types were correctly identified in each instance.
