# HSG-Project-Mosaic (Python3)

***Project Description***

This is a student project (Python3 used) of the University of St. Gallen within the course Programming – Introduction Level.
The goal of the project was to create a mosaic of small pictures, which on the whole imitates a larger picture. Since we, Nikolas and Moritz, are both very interested in art, we decided to take a color spectrum with simple colours and recreate this image with many (1616 to be exact) smaller pictures. 

We focused on bees for the small pictures since they appear in many different colors and we were able to find many bee pictures on Flickr, making the final mosaic target picture more vivid. In the end, the mosaic of 1616 small bee pictures should imitate the large color spectrum image ("Colour_Spectrum_Target.png").

In order to use and test the program, please see the "Instruction" Section below.


***Structure***

Our whole project is divided into 2 parts:

1.	Downloading and resizing of 1616 bee pictures 
    We used Flickr's API to download pictures of bees, as it was relatively easy to use with python. Subsequently we resized all pictures to the same size and saved them to the     "Bees" folder
    
2.  From this, bee-picture folder and our target image (e.g. Rothko painting), we now created a mosaic, matching the avgerage RGB colour values of each bee picture, with the RGB     value of a "pixel" of the target image (target image is divided into 1616 pixels)

Step one is represented in "Download&Resize.py" file, however is not meant to be carried out here (not supposed to be tested as complicated/takes long) 

Step 2 is supposed to be tested/performed, please see "Instructions" below for this.


***Instructions***

1.  Download the "Colour_Spectrum_Target"-image and the "Bees"-folder into a folder on you computer locally (have to be saved in same folder and please don't change names)

2.  Numpy and Pillow (PIL) packages need to be installed on computer locally (https://pypi.org/project/Pillow/)

3.  Copy the code from "Create_Mosaic.py" into your IDE and save the file in the same folder as the "Colour_Spectrum_Target"-image and "Bees"-folder

4.  Run the code file that you just saved (e.g. from terminal). It might take a few minutes to load. Afterward click on the newly created "Output"-image and the mosaic should appear :)

(Note that it might take a little and you might have to press enter a few times)


***Thanks for your interest***

Should you have any questions, do not hesitate to contact nikolas.unger@student.unisg.ch or moritz.kaufhold@student.unisg.ch.

Hope you enjoy the project,

Nikolas & Moritz
