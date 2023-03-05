# Driver-Drowsiness-Detection

#Importing OpenCV Library for basic image processing functions

# Numpy for array related functions

# Dlib for deep learning based Modules and face landmark detection

#Face_Utils for basic operations of conversion



#Initializing the camera and taking the instance
cap = cv2.VideoCapture(0)

#Initializing the face detector and landmark detector
detector = dlib.get_frontal_face_detector()
predictor = dlib.shape_predictor("shape_predictor_68_face_landmarks.dat")






       

    
