# Synchrotron-Simulation-using-OpenGL
 SYNCHROTRON is a particular type of cyclic particle accelerator 
 Synchrotron simulation using C implementation of OpenGL

AIM:To implement an interactive SYNCHROTRON simulation which satisfies the following: i. OpenGL based SYNCHROTRON , which provides options like control over the acceleration of the electrons and light created by the fast moving electrons. ii. Functions like clockwise rotation of electrons and to analyze and study the molecular shape and structure of the object placed opposite to the diffracted light.

Some tweaks that have to be made if objects are not being displayed

glutInitDisplayMode(GLUT_ACCUM|GLUT_RGB); line works on my computer as on few other computers. But on certain computers glutInitDisplayMode(GLUT_DOUBLE|GLUT_RGB); works and not the ACCUM buffer. Be sure to read the comments along the code to have better understanding of the code.

Input keys for the application:

   1. LMB to increase the speed of particles inside the Torus(accelerator), ( minimum 4 clicks required to obtain light )
   2.RMB to decrease the speed of particles inside the Torus(accelerator)
   3.'m' to go to next frame
   4.'n' to go to previous frame
   5.'a' and 'd' to focus the light onto the object under test in the second frame only after the light is generated using step 1

