# DNA-Origami-RNAP



An "X" shaped DNA origami rotor is attached to a strand of DNA that is fed though the enzyme RNA polymerase. The tip of one of the rotor arms is tracked, its movements in time are recorded in the csv file. The x- and y- values in the csv file describe the location of the tip of one of the rotor blades as it moves with the DNA. Each row is a time step with difference between rows = 20 ms

"RNAP Visualization Rough" File:
My first attempt at visualizing the data, the z axes for the 3D plots in this file are the index of each row (as opposed to time)

"RNAP 1.1" File:
Color gradients and 3 dimensions represent the change in time. This notebook showcases 3D line and scatter plots of the data from two different views. 


RNAP Average File:  *** NEWEST STATIC GRAPH FILE IF YOU WANT TO SEE THE MOST POLISHED GRAPHS SO FAR LOOK HERE ***
This shows the static graphs of RNAP activity as function of time on the z axis and displacement from the center on the x and y axis. 
The displacement on the x axis was found by taking the average of the original x data and subtracting that average from each x data value
The same was done to find the replacement on the y axis
