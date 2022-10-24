Welcome to the tracke program spetialize in the tracker of white plastic beads
-----------------------------------------------------------------------------------------------------------------------------------------------------
It is necessary to install the library cv2 

$ pip install pip install opencv-python

The program initialize runnig in python (could be spyder or directly from the terminal of python).

------------------------------------------------------------------------------------------------------------------------------------------------------

The file ''take_data.py'' use the classes defined in file ''trackerclass.py'' to make the tracker. 

The firs cell open the video an read de frames per second (fps). In the second is for the definition of the initial frame and the total duration of the tracker. There also is define the ROI width. The function initialConditionsSelecBox open the first frame and eneble a selection box to chooose the template use to tracker the object of interest. If the templat it's not defined then the tracker can't be possible. Finally, the finction corr execute the algorithm for the tracker of the particle and returns the trayectory. 
