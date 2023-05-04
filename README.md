Download Link: https://assignmentchef.com/product/solved-csci4360-5360-homework-3
<br>
This is a programming assignment. Given a robot equipped with 6 Infrared sensors as shown in the picture below (θ<sub>1</sub>=45<sup>o</sup>, θ<sub>2</sub> = 30<sup>o</sup>, θ<sub>3</sub>= -30<sup>o</sup>, θ<sub>4</sub>=-45<sup>o</sup>. θ<sub>5</sub>= -130<sup>o</sup>, θ<sub>6</sub>=130<sup>o</sup>), write a C++ program that computes the magnitude of drive and direction of turn of the robot movement based on sensor readings.

The sensor readings for three consecutive time steps are given in a data file: readings.dat. (You may download the data file from the course page). For each set of 6 sensor readings, your program should output the turn direction and magnitude in the form: <strong><em>the robot should turn -25 degrees with a magnitude of 0.35</em></strong>).

Use linear magnitude profile for the potential fields implemented for the motor schema.

MAX_DISTANCE of the sensor is set to D =10 cm.

Name your program <strong>pfield.cpp</strong>. Your program should include comments for logically related code segments. It should also have program heading at the beginning of the program which includes information such as the name of the programmer, due date, description of this program.




<strong>Programming requirements: </strong>

<ul>

 <li>Your program reads the data from a data file named “readings.dat” • The program should include at least these 3 functions:</li>

</ul>

o The main function handles the main program logic:  1. loop til the end of the data file is reached

1.1 loop over the 6 sensors:

1.1.1 SENSE:  get sensor information for the

1.1.2 ACT: use repulsive potential field to generate the vector for movement

1.1.3 Add the vector onto the overall sum-of-vectors

1.2 Report direction of movement for the current readings

o A function implements the repulsive potential field o A function that adds two vectors




1







To submit your program, log onto D2L, go to the course page, and submit the program to the Dropbox named “Homework 3”. You may submit multiple times before the due time. All versions of the programs will be kept in your account

<strong><em>readings.dat</em></strong> content:

5 25 20 28 25 2

5 6 4 8 28 25

4 5 20 28 8 12

2