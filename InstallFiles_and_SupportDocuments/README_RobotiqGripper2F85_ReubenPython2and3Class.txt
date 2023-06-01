########################

RobotiqGripper2F85_ReubenPython2and3Class

Code (including ability to hook to Tkinter GUI) to control Robotiq 2F85 Gripper via Serial Modbus (RS-485).

Reuben Brewer, Ph.D.

reuben.brewer@gmail.com

www.reubotics.com

Apache 2 License

Software Revision E, 06/01/2023

Verified working on: 
Python 2.7, 3.8.
Windows 8.1, 10 64-bit
Ubuntu 20.04
Raspberry Pi Buster 
(no Mac testing yet)

########################  

########################### Python module installation instructions, all OS's

RobotiqGripper2F85_ReubenPython2and3Class, ListOfModuleDependencies: ['ftd2xx', 'future.builtins', 'serial', 'serial.tools']
RobotiqGripper2F85_ReubenPython2and3Class, ListOfModuleDependencies_TestProgram: ['MyPrint_ReubenPython2and3Class']
RobotiqGripper2F85_ReubenPython2and3Class, ListOfModuleDependencies_NestedLayers: ['future.builtins']
RobotiqGripper2F85_ReubenPython2and3Class, ListOfModuleDependencies_All:['ftd2xx', 'future.builtins', 'MyPrint_ReubenPython2and3Class', 'serial', 'serial.tools']

Note that the code will work just fine without 'ftd2xx' but will be unable to set the Latency Timer programatically for FTDI USB-to-serial converters.

###########################
