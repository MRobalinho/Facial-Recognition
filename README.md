# Facial Recognition 

## Facial Recognition, some explanation about

Recognize and manipulate faces from Python or from the command line with the world's simplest face recognition library.

### How it works?
The human face, despite the variations from person to person, has a basic composition that does not change, read by the applications as points in common, that vary according to the complexity of the system.

By using logarithms and software that map this pattern to people, it is possible to record only the face or all movements and employ them in the most diverse functions. All have the same principle: detect a face in geometric and logarithmic shapes and then mount it as in a puzzle.

The face recognition system consists of three fundamental phases: <b> face tracking, extraction and selection of facial features, and face recognition</b>.

![ScreenShot](https://github.com/MRobalinho/Facial-Recognition/blob/master/Doc/678191.jpg)

The first step is to inform the coordinates of the characteristic points of the eyebrow, eyes, nose and mouth face.

Now the second step is to store the FACE and an ID (name if you prefer) for later authentication. In my Face-recognition_4 example I used an excel file with the photo's name and the person's name. In the Face-recognition_5 and 6 example I used the filename already named with people's names.

The first step is to identify through a camera (digital, webcam, cell phone, among others) all or some of these points in common, such as the two eyes and the distance between them, the nose and its length, the mouth, the cheeks and the chin, thus limiting the shape of the face and the space occupied by it.

In our algorithm ( <b>face_recognition</b> ) the system find the points: 
<br/>chin 
<br/>left_eyebrow 
<br/>right_eyebrow 
<br/>nose_bridge 
<br/>nose_tip 
<br/>left_eye 
<br/>right_eye 
<br/>top_lip 
<br/>bottom_lip

These points are written and stored in the format of algorithms in a database, which recognize them through calculations. It sounds easy, but it all took some time to consolidate with the efficiency we see today.

The first application is also the simplest: to detect faces and small changes in it to improve portrait quality. Nowadays, practically every camera has a smile detection system, which automatically shoots when an element of the photo smiles - that is, when it changes the shape of the mouth relative to what was recorded on the camera.

https://www.tecmundo.com.br/camera-digital/10347-como-funcionam-os-sistemas-de-reconhecimento-facial.htm

## Requirements
Python 3.3+ or Python 2.7

## Documentation to install
pip3 install face_recognition pip install dlib

Face Recognition GithubÇ https://github.com/ageitgey/face_recognition

pip install cmake

Need CMAKE installed to install the file requirements.txt 
pip install -r requirements.txt --no-color


Need Install the follows packages (The packages are in the file requirements.txt)


>face_recognition_models 
>Click>=6.0 
>dlib>=19.3.0 
>numpy 
>Pillow 
>scipy>=0.17.0


You can download CMake for Windows here : http://www.cmake.org/cmake/resources/software.html

## My definitions
I have a folder with my images for training , folder images

in that example (Face-recognition_6) i use the name file to extrat the person name. All the images have the person name and a '-' to numerate. Example (manuel-1.jpg) i find the '-' in the filename and i extract the relevants positions to obtain the person name.


## RESULT can be watched in:

[![DETECTION VIDEO](https://img.youtube.com/vi/vOokYj52v6Y/0.jpg)](https://www.youtube.com/watch?v=vOokYj52v6Y)
<br/>https://youtu.be/vOokYj52v6Y


[![DETECTION VIDEO](https://img.youtube.com/vi/xDCV0f_h3t8/0.jpg)](https://www.youtube.com/watch?v=xDCV0f_h3t8)
<br/>https://youtu.be/xDCV0f_h3t8
