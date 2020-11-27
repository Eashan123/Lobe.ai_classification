# Lobe.ai_classification

Image classification using Lobe.ai.

Model exported as tensorflow

`signature.json` is created by Lobe and contains information about the model such as label names and the image size and shape the model expects.

`tf_example.py` is a simple script to quickly test your exported model. It takes a path to an image on your file system, prepares the image and returns the predicted class and confidence level.

`requirements.txt` is where the Python libraries and version information required to run the script are found.

You will need Python 3.6 and the path to an image on your machine to test.

endpoint [POST]:

http://0.0.0.0:7002/predict

key{text} path -> value (path to image)
