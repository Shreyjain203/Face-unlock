# Face-unlock
This repo has 2 ipynb files, one is for adding face and other is for recognition. CSV files are used to store every data possible.


The jpg files 0,1,2... are the images saved for some verified persons.
facedata.csv contains the respective names of that jpg files.

Actual face recognition code snippet is inside the Face Recognition.ipynb file
And after every sucessful login/verification the name of the personal along with date and time of login is stored in facedatarecord.csv file

Add Face.ipynb file is used to add new user's face id and the name of it's jpg file will b a number following the last no.jpg file and name poining that image will be stored in next row of facedata.csv file.
e.g., if someone add his/her face and there are already 5 person's face data(0,1,2,3,4) then his jpg file would be 5.jpg 
if a person wants to record his face data manually, he/she can save his jpg file as a no. following the biggest no of the jpg file and also have to save his/her name in the next row of facedata.csv file 
