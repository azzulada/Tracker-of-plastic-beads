
Welcome to the tracker program optimize to compute trayectories of white plastic beads with a dark background.

-----------------------------------------------------------------------------------------------------------------------------------------------------

It is necessary to install the library cv2 

$ pip install pip install opencv-python

The program initialize runnig in python (could be spyder or directly from the terminal).

------------------------------------------------------------------------------------------------------------------------------------------------------

The file ''take_data.py'' uses the classes defined in file ''trackerclass.py'' to make the tracker. 

The first cell opens the video an read the frames per second (fps). The second one is for the definition of the initial frame and the total duration of the tracker. There also is defined the ROI's width and height. The function ''initialConditionsSelecBox'' opens the first frame and eneble a selection box to chooose the template use to tracker the object of interest. Press ''Enter'' once the rectangle is made for establish the template.  If the template it's not defined then the tracker can't be possible. Finally, the function ''corr'' execute the algorithm for the tracker of the particle and returns the trayectory. 

------------------------------------------------------------------------------------------------------------------------------------------------------

In case of any query write to gabrielvolonnino@gmail.com, azulmariabrigante@gmail.com, Cori.revora@hotmail.com 
