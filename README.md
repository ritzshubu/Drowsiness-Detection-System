# Drowsiness-Detection-System Using Haar Classifier
A machine learning algorithm to detect the drowsiness of a driver

Python Libraries Required:

(Working Internet Required)

[Recommended To Use Anaconda]
    
    OpenCV
        openCV for computer vision
    
    scipy (pip install scipy)
       To compute the Euclidean distance between facial landmarks points in the eye aspect ratio calculation

    numpy (pip install numpy)
        numpy for basic processing and calcutions

    imutils (pip install imutils)
        to make working with OpenCV easier.

    pyglet (pip install pyglet)

        for working of alarm
    dlib
        To detect and localize facial landmarks we’ll need the dlib library
        
   NOTE: YOU NEED TO DOWNLOAD pre-trained facial recognisation dat file "shape_predictor_68_face_landmarks.dat" from my gdrive 
   ( https://drive.google.com/drive/folders/1aJptGw4UltwvL-UvFa-cbQEKf4_xcJuU?usp=sharing )
   You can also download the whole folder from gdrive.
   
   Finally, If everything goes without any interruption. Run the code by:
   python main.py -p shape_predictor_68_face_landmarks.dat -a alarm.mp3

