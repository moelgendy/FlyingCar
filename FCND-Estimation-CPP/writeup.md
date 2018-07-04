# Estimation Project Writeup #

### Scenario 6: Sensor Noise ###

#### Completed ####
```
Simulation #8 (../config/06_SensorNoise.txt)
PASS: ABS(Quad.GPS.X-Quad.Pos.X) was less than MeasuredStdDev_GPSPosXY for 68% of the time
PASS: ABS(Quad.IMU.AX-0.000000) was less than MeasuredStdDev_AccelXY for 69% of the time
```

![sensor noise](images/scenario6.gif)


### Scenario 7: Attitude Estimation ###

#### Completed ####

```
Simulation #13 (../config/07_AttitudeEstimation.txt)
PASS: ABS(Quad.Est.E.MaxEuler) was less than 0.100000 for at least 3.000000 seconds
```
![scenario7](images/scenario7.gif)


### Scenario 8: Prediction Step ###

#### Completed ####

![scenario8](images/scenario8.gif)

### Scenario 9 ###

#### Completed ####

![scenario9](images/scenario9.gif)


### Scenario 10: Magnetometer Update ###

#### Completed ####

```
Simulation #3 (../config/10_MagUpdate.txt)
PASS: ABS(Quad.Est.E.Yaw) was less than 0.120000 for at least 10.000000 seconds
PASS: ABS(Quad.Est.E.Yaw-0.000000) was less than Quad.Est.S.Yaw for 73% of the time
```
![scenario10](images/scenario10.gif)

### Scenario 11: Closed Loop + GPS Update ###

#### Completed ####

```
Simulation #53 (../config/11_GPSUpdate.txt)
PASS: ABS(Quad.Est.E.Pos) was less than 1.000000 for at least 20.000000 seconds
```
![scenario11](images/scenario11.gif)
