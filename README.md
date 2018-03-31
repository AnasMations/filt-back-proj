# filtbackproj

This is Python code for a very basic filtered backprojection algorithm used in CT and SPECT imaging. Effectively it's a port for MATLAB code generated by Waqas Akram, Steve Gee, Charles Gamiz, Christine Pan, and Justin Romberg which for the time being can be found here: 

https://www.clear.rice.edu/elec431/projects96/DSP/index.html

This code does not explicitly use Radon transform functions. In doing so perhaps it can be clearer to the user what operations are actually taking place in the reconstruction process, as the acquisition of projections and the backprojection process is visualized projection-by-projection. Perhaps it also allows the freedom to tinker with said operations. The backprojection process was originally displayed projection-by-projection on Ubuntu 14.04LTS, but it doesn't appear to work properly on other machines. Probably need to look at graphical backend usages.

![alt text](./figure_2.png)
