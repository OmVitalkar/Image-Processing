# Image-Processing
Identifying Images Using AI 

Face Detection and Re-identification Demo
This is a demo program to demonstrate how person or face detection DL model and re-identification model This program finds the objects such as person or face from the multiple images, then assign ID and match objects in the pictures.
The demo program suppors multiple camera or movie file inputs (the program should work with more than 2 inputs).  
This program calculates the cosine distance of those feature vectores of the objects to check the object similarity.  
The found objects are registered to a database with the created time. The time in the record will be updated everytime the record is used so that the program can check the elapsed time from the last use. The record will be evicted when the specified time passes.  
