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


![image](https://user-images.githubusercontent.com/67355283/163259224-9c886215-c274-4dae-86e2-ec99eeecc33a.png)

 
fig4

As for finishing the PLL loop we will design a frequency divider

as shown fig 5


![image](https://user-images.githubusercontent.com/67355283/163259443-48659111-87f6-4619-aea3-b2dcc02ff700.png)

 
fig 5

 after finshing the desing and the testing we move to the layout for each phase :

Frequency Divider

![image](https://user-images.githubusercontent.com/67355283/163259856-508f04c7-7645-48de-a37b-fa23d08f83f4.png)

 
Phase Frequency Detector


![image](https://user-images.githubusercontent.com/67355283/163259962-9b46a119-7ac5-40f5-a893-62b3611dc236.png)

 
Mux

![image](https://user-images.githubusercontent.com/67355283/163260069-2abc665b-c20d-41cf-86d0-6001ccacfd03.png)

 

Charge Pump


![image](https://user-images.githubusercontent.com/67355283/163260260-842e908a-6ffe-4a42-85f1-9efcb281b3cd.png)


 

Voltage Controlled Oscillator

![image](https://user-images.githubusercontent.com/67355283/163260377-1492c22d-552a-4632-93a3-c43ae525b38b.png)


 

After layinout each phase for each PLL , now will combine all layout to finaly be shown as bellow:


![image](https://user-images.githubusercontent.com/67355283/163260592-e1e805a8-e087-4718-90f1-cd78ef8f8ab0.png)

 










