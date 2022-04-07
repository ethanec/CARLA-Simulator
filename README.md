# CARLA-Simulator
A simulator that allows vehicle doing autonomous driving research

OS: Ubuntu 18.04
/ version: 0.9.8

To download the whole Carla Simulator, visit https://carla.org/2020/03/09/release-0.9.8/

## Execute a manual control scenario on CARLA-Simulator 
1. Execute CarlaUE4.sh in your Carla directory on Ubuntu 

    For me, my Carla directory is cd ~/Carla_0.9.8 
    ```
    cd ~/Carla_0.9.8 
    ./CarlaUE4.sh 
    ```
     ![](https://i.imgur.com/KsycU8E.jpg)

2. To change the scene of the map, execute config.py (optional) 
    ```
    cd PythonAPI/util 
    python config.py --map Town05 
    ```
    ![](https://i.imgur.com/fM1XWSO.jpg)

3. Run python file 
    To figure out what was revised in the python file, find “YC” in comment. 
    ```
    cd PythonAPI/example 
    python manual_control_mec.py  
    ```
    ![](https://i.imgur.com/gz8UUpT.jpg)
