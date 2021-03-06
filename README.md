
# Three body problem

<center>

![threebody](threebody/Vis/Gifs/Three_body.gif)

</center>

[![Documentation Status](https://readthedocs.org/projects/project-three-body-problem/badge/?version=main)](https://project-three-body-problem.readthedocs.io/en/latest/?badge=main)

## Authors

- Touzani Amine (amine.touzani@etu.umontpellier.fr)
- Niasse Gueladio (gueladio.niasse@etu.umontpellier.fr)
- Fattouhy Mohamed (mohamed.fattouhy@etu.umontpellier.fr)
- El Kaïm Laura (laura.el-kaim@etu.umontpellier.fr)

## Three Body Problem

The goal of this project is to solve the Three Body Problem and produce a video (or gif) representing the motions of the sun, mars and the earth, in three dimensions.

The Three Body Problem is a special case of the n-body problem. In astronomy, this problem consists in determining the motion of three celestial bodies moving under no other influence than their mutual gravitation.
   
Here, we will be interested by the sun, mars and the earth. And our starting point will be based on the initial positions and speeds, and also the masses of each of these bodies.

In few words, this problem consists in finding mathematical solutions to differential equations with well chosen initial conditions. 
These differential equations describe the motions of three bodies attracting each other under the effect of gravity.

## To install the package

The package is hosted on [Test.Pypi](https://test.pypi.org/project/threebody/), to install it type in a terminal :

```{bash} 
$ pip install -i https://test.pypi.org/simple/ threebody
```

## Documentation

The documentation of this package is available [here](https://project-three-body-problem.readthedocs.io/en/latest/?badge=latest).

## Video presentation

A presentation is available on [youtube](https://www.youtube.com/watch?v=hMskyuzyi0k).

## Plan

- Creation of the repository and branches.
- Solving differentials equations to associated the problem.
- Differentials equations programming for 2 bodies.
- Differentials equations programming for 3 bodies.
- Unit tests.
- Visualization part (in 2D then 3D).
- Creation of gif or mp4.
- Documentation.
- Beamer.

## Tasks distribution

- Gueladio and Mohamed take care of the code : Gueladio will begin by solving the problem when we take only 2 planets. Mohamed will be focus on three planets.  More precisely, the resolution of these differentials equations will be done by the RK4 method (Runge-Kutta 4).  
Using the `Numba` package to speed up numerical resolution.  
Then they will focus on documentation.

- Laura and Amine will be interested in visualization, in 2D and 3D.  
Creation of a program generating 200 images to visualize the evolution of the planets in their respective orbits according to their mutual attractions.  
Using the package `matplotlib3D`.  
Then they will focus on unit test.


The goal is to get something like this in motion (gif or mp4):

<center>

![threebody](threebody/Vis/Images/Images_2/file_000.png)

</center>
