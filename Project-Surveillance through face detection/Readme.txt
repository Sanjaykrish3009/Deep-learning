Necessary File and Images

For proper running of code, Please store the Data as follows:

* Create a folder named WIDERFACE in your google drive
* Dowload and Upload WIDER_train (WIDER Face Training Images)
		 and wider_face_split (Face Annotations) 
		 from http://shuoyang1213.me/WIDERFACE/ for the image datasets and labels
* Both the above WIDER_train and wider_face_split folders must be present inside the WIDERFACE folder created before
* Also upload the images submitted in the folder DL-FinalProject-Images to the WIDERFACE folder in your google drive
* Note that the above images are directly inside WIDERFACE folder, not again inside DL-FinalProject-Images folder. 
  DL-FinalProject-Images was maintained just for submitting
  
Overall File Heirarchy

MYDRIVE |
        |- WIDERFACE |
                     |- WIDER_train - |
                                      | - Images (Contains folders inside each folder again with many image files)
                     |- wider_face_split - |
                                           |- readme.txt
                                           |- wider_face_train_bbx_gt.txt ( used to draw boundaries of face images)
                                           |- ...
                                           |- ... other necessary files depicting the image file lists and stuff
                     |- img.jpeg
                     |- img1.jpg
                     |- img2.jpg
                     |- img3.jpg
                     |- img4.jpg
                     |- img5.jpg
                     |- img6.jpg
                     |- img7.jpg
                     |- img8.jpg
