# RDPS
This project consist on designing an SoC from scratch

As first step we start desging a PLL clock byb using  Google-Skywater 130nm node.

We will design this PLL by starting dsigning a Phase Freqency Detector , the simulation is shown at the fig 1 for up signal and down signal at fig 2 simulated with ngspice

![image](https://user-images.githubusercontent.com/67355283/163258394-fe32b510-f768-4d3f-bcc7-3bb8883da135.png)

 
fig 1

 ![image](https://user-images.githubusercontent.com/67355283/163258942-15a8e1be-91c3-408d-9e7c-616cfe426cc0.png)
fig 2


As for the next step will design a Charge pump as shown at the fig 3 for up signal and fig 4 for down signal

![image](https://user-images.githubusercontent.com/67355283/163259101-efecef59-f641-4cb5-9203-c54ed5c12c6b.png)

 
fig 3

 
fig4

As for finishing the PLL loop we will design a frequency divider

as shown fig 5

 
fig 5

 after finshing the desing and the testing we move to the layout for each phase :

Frequency Divider

 
Phase Frequency Detector

 
Mux

 

Charge Pump


 

Voltage Controlled Oscillator

 

After layinout each phase for each PLL , now will combine all layout to finaly be shown as bellow:

 










