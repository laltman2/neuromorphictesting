# Physical Learning Metamaterials Circuits Lab ![Version](https://img.shields.io/badge/version-2.0.0-blue)
Sending and receiving data from Arduino using Pyserial library. 

## Setup

Here are the steps to run this project

### a. Open test_comms.ino and open files Comms.h and Comms.cpp

Make sure that you're connected to an arduino (I used UNO). Then upload the code. 

### b. Open Test_Comms.ipynb. Input the correct seiral port. 

You can find the serial port for Mac with the terminal command below. 
```
ls /dev/tty.*
```
Then run everything. 

## Parameters

Parameters for the physical learning network: 

```
//Physical Leanring Parameters 
int ETA; // eta 
int GMN; // Gmin 
int ALF; // alpha (learning step time) in microseconds
int EPO; // number of epochs
int MES; // number of measurement steps
int NMS; // number of times to take each measurement
int NSR; // number sources
int NTR; // number targets 
int NEG; // number of edges
int NDR; // number train data points
int NDS; // number of test data points
```

Associated with the University of Pennsylvania. 
