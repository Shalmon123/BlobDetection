# BlobDetection

You need to have opencv installed on your Pc and added to the path variables (windows) and your terminal path (linux)

The Python script and a few example images are included.

#INSTRUCTIONS 

Put the photo and the script in the same folder.

Edit the line <im = cv2.imread("blob.jpg", cv2.IMREAD_GRAYSCALE)>

  replace "blob.jpg" to "NAME-OF-YOUR-IMAGE"
  
open a cmd window/ powershell/ terminal in the folder containing the script and run with

  python blob.py
  
it will show the number of blobs in the cmd/ terminal window and show a photo highlighting all the blobs/spots.

Its not perfect but gets the job done quickly. You can tweak the parameters in the python file to make it more accurate according to your image.
