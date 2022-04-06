# Klipper Macro - Speed Test Moves

## Install
Download macro file and copy it to your printer configuration folder then include it with
```
[include speed_test_moves.cfg]
```

## Parameters
* X=0/1 - generate moves on X axis, default value 1
* Y=0/1 - generate moves on Y axis, default value 1
* Z=0/1 - generate moves on Z axis, default value 0
* SPEED=1000 - mm/s movement speed, default is 20 mm/s
* ACC=500 - acceleration, default is 500 mm/s
* MOVES - how many moves to generate, default is 1

## Examples
```
SPEED_TEST_MOVES
```
* generates one random move at 20 mm/s^2, 500mm/s acceleration using X and Y axis

```
SPEED_TEST_MOVES X=0 Y=0 Z=1
```
* generates one random move at 20 mm/s^2, 500mm/s acceleration using Z axis

```
SPEED_TEST_MOVES ACC=10000 SPEED=250 MOVES=100
```
* generates 100 random move at 250 mm/s, 10000 mm/s^2 acceleration using x and y axis
