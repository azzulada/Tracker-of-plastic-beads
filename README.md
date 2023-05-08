
Welcome to the tracker program optimized to compute trayectories of white plastic beads with a dark background.

-----------------------------------------------------------------------------------------------------------------------------------------------------

Before starting, ensure that the following libraries are installed on your operating
system: ‘numpy’, ‘matplotlib’, ‘openCv’ and ‘scikit-image’. These libraries are necessary
for the program to run properly. Once this is well done, is possible to execute the tracking
with the following steps

**1. _Specify the video file and initial parameters:_** Open the 'take_data.py' file and assign the value 
     of the video file name to the variable 'videoName'. Ensure that the video file is in the same folder as the script. Choose the initial time and duration  of the tracker and write them in to the variables with the same name. The height and width of the Region of Interest (ROI) can be settle into the attribute 'observationWidth'. Could be convenient make this region smaller when the particle is too close to another one so the tracker don't  mix the objective.

**2. _Execute the module:_**  Run the 'take data' module on Python by typing 'python take\_data.py' in the command prompt or terminal. Make sure that the'trackerclass.py' file is also present in the same folder as the 'take data' file.

**3. _Select Template:_**  After executing the module, an emergent window will appear. Use the rectangle tool to select the particle you want to track. Press and hold the left mouse button to draw a rectangle around  the particle. Once you have selected the particle, press the 'ENTER' key to define the template. If you want to cancel the selection process, press the 'c' key.

**4. _Track the particle:_** After defining the template, the script will start tracking the particle automatically in the window. The particle's position will be marked with a red rectangle, while the ROI will be marked with a cyan rectangle. If the particle is too close to another one, you can adjust the size of the ROI to make it easier for the tracker to follow the objective.

**5. _Review of the tracking results:_** Once the tracking is complete, a graph of the trajectory will be plotted automatically. The tracking results will be saved in the 'xcorr' and 'ycorr' variables, which contain the x and y coordinates of the particle at each time step. 
------------------------------------------------------------------------------------------------------------------------------------------------------

In case of any query write to azulmariabrigante@gmail.com, gabrielvolonnino@gmail.com, Cori.revora@hotmail.com 
