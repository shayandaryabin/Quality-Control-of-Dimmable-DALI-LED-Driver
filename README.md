# Quality-Control-of-Dimmable-DALI-LED-Driver
Developed test automation to verify the functionality of test setup.
user can put the measured values in data.json file.
The measured values through oscilloscope or other electrical measurement devices represent the values in i_MEAS and u_MEAS in data.json file.
The measured values throuhh LED-Driver(DUT) represent the values in i_DUT and u_DUT in data.json file.
The python code is written in PyCharm IDE, and gives (PASS/FAIL) results through pytest framework. 

*The values in data.json file are assumed for 30 W DALI dimmable LED driver. 

MEAS and DUT classes are in math_func python file.
test class is in test_math_func python file. 
