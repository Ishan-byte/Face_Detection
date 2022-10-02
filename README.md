 Facial Detection App:
    Application that helps detecting facial objects in an image. However, I will try to make it more dynamic so that it can be implemented for any kind of object detection.

Development Steps:

Environment Setup and Importing necessary libraries and dependencies

    Libraies:
        For different purposes, multiple libraries were must to be installed, such as tensorflow, matplotlib open-cv and so on. However, there are two new libraries for me:

    Labelme: 
        It is used for image annotations where it will help to determine the coordinates of an object in  an image.

    Albumentations:
        It is used for image augmentation. Augmentation or any kind of Data augmentation can be called as the process of amplifying the number of our datasets by modifying the existing data in our dataset. In our case it is images so modifying the data might include different colorr patterns, cropping and so on.

    Environment:
        I started this project by creating a virtual environment and Jupyter notebook. While installing modules, it might get tricky as I am currently stuck in solveing a legacy install error for labelme and matplotlib.