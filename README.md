# Face-Unlock
Unlock your face using openCV and Python 

     $ python face_unlock.py -h
usage: face_unlock.py [-h] -n  -p

Enter the name & directory of the person and image.

optional arguments:

  -h, --help    show this help message and exit
  
  -n , --name   Give the name of the person
 
 -p , --path   Give the path of the video

#USAGE

Eg: 
    
    $ python face_unlock.py -n "Rajath" -p "trail.mp4"
   
    $ python face_unlock.py --name "Rajath" --path "/home/usr/Downloads/Brave\ Downloads/trail.mp4"
   
The program will create and capture 100 face images from the video file and store it in 'faces/user/' folder. So make sure to create faces/user/ folder in the present directory or working directory before using the face_unlock.py script.



