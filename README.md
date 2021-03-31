Before you jump into executing the code create a conda environment including the necessary dependencies by running the following command:

conda env create --file environment.yml

The application works by running the TeachingSlate.ipynb and the video feed can be changed by the changing the videofeed parameter to 
cv2.VideoCapture(videofeed).
The videofeed is currently from an app called as droidCam (https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&hl=en_IN&gl=US)

The yolo model used for hand detection is taken from https://github.com/cansik/yolo-hand-detection

The model weights for cross hands tiny is available in https://github.com/cansik/yolo-hand-detection/releases/download/pretrained/cross-hands-tiny-prn.weights

The setup to the yolo model is briefly explained in https://github.com/cansik/yolo-hand-detection/blob/master/README.md

Credits:
Florian Bruggisser https://github.com/cansik
