# Estimation Project Writeup #

### Step 1: Sensor Noise ###

#### Completed ####
```
Simulation #8 (../config/06_SensorNoise.txt)
PASS: ABS(Quad.GPS.X-Quad.Pos.X) was less than MeasuredStdDev_GPSPosXY for 68% of the time
PASS: ABS(Quad.IMU.AX-0.000000) was less than MeasuredStdDev_AccelXY for 69% of the time
```

![sensor noise](images/scenario6.gif)


### Step 2: Attitude Estimation ###

#### Completed ####

```
Simulation #13 (../config/07_AttitudeEstimation.txt)
PASS: ABS(Quad.Est.E.MaxEuler) was less than 0.100000 for at least 3.000000 seconds
```
![scenario7](images/scenario7.gif)