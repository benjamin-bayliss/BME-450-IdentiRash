# Title
IdentiRash 

## Team Members
benjamin-bayliss, gerniegalvan-prog, nacii999

## Project Description 
This project is meant to differentiate different rashes on skin. 
The goal is to itentify the location of a rash in an image and plot a bounding box around it.
We plan for the model to be able to differentiate different rashes and plot a percieved "diagnosis"
of the type of rash. 
The training data we need are skin images containing a visible rash, a bounding box annotation (x,y,width,height)
marking the rash region and a class label indentifying the rash type. Based on some preliminary research, we have some
datasets available for us to use. Mainly the ISIC archive with 70,000+ images of skin lesions with masks (but it seems to be mostly melanomas)
, HAM10000 which also has many images, or DermnetNZ with a great variety of skin conditions. 
