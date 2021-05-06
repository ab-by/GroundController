# GroundController
Mission Planning through python code in 2D

Install the mono file which will help us to run few windows applications in linux 

                                              
                                                  sudo pip install mono 

Now go to this website and download the version 1.3.33 which gets saved in downloads and unzip it.

                               //firmware.us.ardupilot.org/Tools/MissionPlanner/archive/

On addition to this get these installed as well

                                                    sudo pip install mavproxy

                                            sudo pip install pymavlink==2.4.8


Now open a terminal and run :

                    
                          dronekit-sitl copter



In another terminal run


                  mavproxy.py --master tcp:127.0.0.1:5760 --sitl 127.0.0.1:5501 --out 127.0.0.1:14549 --out 127.0.0.1:14450


Now cd to the location where you have unzipped the downloaded file and write this cmd in the third terminal 

                                   sudo mono MissionPlanner.exe


Now cd to the location where this move.py file got downloaded and run this cmd in the 4th terminal.


                                         python move.py


Wait for sometime the python file first gets executed in the terminal and then in the GroundController tab.

