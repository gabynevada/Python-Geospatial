# PyProj

## Pyproj Prerequisites
#### Download and install Visual C++ Compiler for Python 2.7

https://www.microsoft.com/en-us/download/details.aspx?id=44266

#### Download and install .Net Framework 3.5

https://www.microsoft.com/en-us/download/details.aspx?id=22

## Install Pyproj

+ Open a Command Prompt
+ Run the following command
```
python -m pip install pyproj
```
+ Pyproj was installed!

## Test Pyproj Installation

#### Distance between 2 points
+ Go into the python command line or equivalent
+ To open the python command line in the Command Prompt type:
```
python
```
+ Run the following code
``` python
import pyproj
lat1, long1 = (37.809662, -122.410408)
lat2, long2 =(37.784161, -122.4014489)
geod =  pyproj.Geod(ellps="WGS84")
angle1, angle2, distance =  geod.inv(long1, lat1, long2,lat2)
print "Distance is %0.2f meters" %  distance
```
+ The print result must be **Distance is 2938.35 meters**
+ If correct then pyproj installation was succesful
