EC 463: Senor Design Mini Project Report

  Our hardware mini project is based on the wifi module on raspberry pi; the goal is to collect data on electronic devices including cars with hotspot activity within 20 meter radius. We were able to get both wifi_scan.py and bluetooth files to work using bt_scan.py & ble_scan.py on our raspberry pi system. 
  
  We set up our test in the Photonics building room pho 111 adjacent to the windows where there are cars coming both dividers as well as the bridge next to photonics. The change we made to the wifi_scan.py stem around the parameter to measure and collect 4 criteria when it scans for nearby electronic devices. After scanning for 30 mins we then parse the information into a json file for analysis and compile a graph of the wifi module detection over the period of time when it's actively looking for wifi. We expected fluctuation around cars from moving in between the roads and attempting to find new unique devices.

Those are the 4 graph that we get based on using different fraction of time device must be detected to be declared stationary.

The first graph is using the default value,0.5.
![0 5](https://user-images.githubusercontent.com/90575789/133714459-782a958a-ae83-4881-8f02-4d0774f23684.png)
The second graph is using the 0.75
![0 75](https://user-images.githubusercontent.com/90575789/133714533-08389b74-4017-4765-b52c-d0f81bbbd1ed.png)
The second graph is using the 0.9
![0 9](https://user-images.githubusercontent.com/90575789/133714604-09d5d82b-a584-4a92-81ac-ada484cb467c.png)
The second graph is using the 0.25
![0 25](https://user-images.githubusercontent.com/90575789/133714606-bf093686-88fa-4765-b49b-c050580fb444.png)
