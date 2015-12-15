# Practice 2014 - 07: The Big Eye in the Sky

## Background
The Eye of Sauron is in the middle of Mordor. He needs to track the tricksy
hobbitses as they trek across the land; to do so, the Eye at the top of the
Tower must rotate so that it has a good view.

The eye is at coordinates (0,0) facing due east. Given a coordinate in the first
quadrant, output the number of degrees from the x-axis to rotate the Eye so that
it faces the hobbits.

## Description

### Input
The input is a series of lines representing integer coordinates of the
hobbitses as an x and y value. All (x, y) coordinates will be in the first
quadrant. The coordinate (0,0) marks the end of input.

### Output
For each test case, output to a newline the number of
degrees (rounded to the closest integer) to rotate the Eye. Note that
each test case is rotating from the x-axis, not from the previous
orientation of the Eye.

## Sample
### Input
```
5 5
9 15
12 6
0 4
0 0
```

### Output
```
45
59
27
90
```
