# GDAL

## Install GDAL for Python 2.7.14
### 32 bit Version
+ Download Core Installer at:
  + http://download.gisinternals.com/sdk/downloads/release-1500-gdal-2-2-3-mapserver-7-0-7/gdal-202-1500-core.msi
+ Install GDAL Core with Typical Settings
+ Download Python 2.7 Binding at:
  + http://download.gisinternals.com/sdk/downloads/release-1500-gdal-2-2-3-mapserver-7-0-7/GDAL-2.2.3.win32-py2.7.msi
+ Install GDAL Python Binding

### 64 bit Version
+ Download Core Installer at:
  + http://download.gisinternals.com/sdk/downloads/release-1500-x64-gdal-2-2-3-mapserver-7-0-7/gdal-202-1500-x64-core.msi
+ Install GDAL Core with Typical Settings
+ Download Python 2.7 Binding at:
  + http://download.gisinternals.com/sdk/downloads/release-1500-x64-gdal-2-2-3-mapserver-7-0-7/GDAL-2.2.3.win-amd64-py2.7.msi
+ Install GDAL Python Binding

## Add Path Variables
+ Go to Control Panel
+ Search for Environment
+ Click on Edit the System Environment Variables
+ Click on Environment Variables
### Add GDAL Path
+ Under the System Variables Pane, find the "Path" variable, and click on Edit.
+ Click on new and type:
+ For GDAL 64 bit:
```
C:\Program Files\GDAL
```
+ For GDAL 32 bit:
```
C:\Program Files (x86)\GDAL
```
+ Click Ok
### Create GDAL Data Path
+ On the System Variable Pane, click on new
+ On the variable name type:
```
GDAL_DATA
```
+ On the Variable Value type:
+ For 64 Bit:
```
C:\Program Files\GDAL\gdal-data
```
+ For 32 bit:
```
C:\Program Files (x86)\GDAL\gdal-data
```
+ Click Ok
### Create GDAL Driver Path
+ On the System Variable Pane, click on new
+ On the variable name type:
```
GDAL_DRIVER_PATH
```
+ On the Variable Value type:
+ For 64 Bit:
```
C:\Program Files\GDAL\gdalplugins
```
+ For 32 bit:
```
C:\Program Files (x86)\GDAL\gdalplugins
```
+ Click Ok

## Testing GDAL

+ Open a new Command Prompt
+ Type **gdalinfo --version**
+ If you get a similar response to this, GDAL is correctly installed
```
C:\Users\myuser>gdalinfo --version
GDAL 2.2.3, released 2017/11/20
```




