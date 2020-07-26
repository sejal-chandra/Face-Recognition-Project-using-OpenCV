# Face-Recognition-Project-using-OpenCV
Face recognition is now done for various applications. The use of face_recognition module made it an easier task which provides a range of functions which can be used to perform several operations with the images.

![face](https://user-images.githubusercontent.com/50629545/88485109-2ec39a80-cf91-11ea-97c7-f08b7d3a361b.png)

<BR>
The commands used are:
<BR>
pip install cmake
<BR>
pip install dlib (I used 2017 version)
<BR>
pip install face-recognition
<BR><BR>

**This project aims to build a face recognition system along with marking attendance through live webcam feed. The attendance is saved in a CSV file which can also be connected to a database such as SQL.**
<BR><BR>
APPLICATION
<BR>
This is a very useful application for marking the attendance of students during online classes. The images of students can be stored in a database using which the faces of students during online class can be matched and the name and current time can be recorded.

<BR><BR> FUNCTIONS USED
<BR>
* cvtColor(): It is present in cv (computer vision) module which is used to convert images from one color space to another. Here, we have converted the images from BGR to RGB.
* face_encodings(): It is a function present in face_recognition module which returns the 128-dimension face encoding for each face in the image.
* face_locations(): Present returns an array of bounding boxes of human faces in a image. We have used it to find the locations of image recognised through live webcam feed.
* compare_faces(): It compares a list of face encodings against a candidate encoding to see if they match.
* face_distance(): Given a list of face encodings, compare them to a known face encoding and get a euclidean distance for each comparison face. The distance tells you how similar   the faces are.
