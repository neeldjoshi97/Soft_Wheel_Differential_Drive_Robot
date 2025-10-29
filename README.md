# Soft-Wheeled Differential Drive Robot

This repository provides a brief overview of the team research project for [24-673 Soft Robots: Mechanics, Design, and Modeling](https://www.meche.engineering.cmu.edu/education/courses/24-673.html) course taught by [Prof. Carmel Majidi](https://www.meche.engineering.cmu.edu/directory/bios/majidi-carmel.html) at [Carnegie Mellon University](https://www.cmu.edu) (CMU).

## Overview

In this research project, our team developed an inflatable/deflatable soft wheel system designed for wheeled robotic platforms. The key idea lies in dynamically controlling the inflation levels of the wheels on either side of the robot, thereby altering their effective radii. This differential in wheel size induces a natural curvature in the robot’s trajectory, enabling smooth and intuitive directional control $-$  without relying on traditional steering mechanisms (which do not work so well with softer materials).

By modulating air pressure within the wheels, our robot can seamlessly turn left or right, offering a lightweight, adaptable, and mechanically simplified solution for locomotion in soft robotics.

## Acknowledgement

My friend and teammate in this project, Sidhant Gupta originally came up with this 'differential-drive-in-soft-robots' idea.

## Motivation [[1]](#references)

Deploying soft-wheeled robots on ground has always been a challenge.

<figure style="text-align: center;">
    <img src="images\grousered_wheel.png">
    <figcaption style="text-align: center;">
        Figure 1: The grousered wheel from previous research
    </figcaption>
</figure>

## Making

For building components for the soft wheel, we utilised the CMU makerspace called [TechSpark](https://engineering.cmu.edu/techspark/) in the College of Engineering.

<figure style="text-align: center;">
    <img src="images\deflated_inflated.png">
    <figcaption style="text-align: center;">
        Figure 2: Our soft wheel in deflated (left) and inflated (right) state
    </figcaption>
</figure>

## Physical Evaluation

I was in-charge of making plans for testing the soft wheel for:
- Study traction on different types of surfaces with varying inflation of the wheel
- Characterise slipping on different types of surfaces with varying inflation of the wheel

<figure style="text-align: center;">
    <img src="images\testing_carousel_bed.png">
    <figcaption style="text-align: center;">
        Figure 3: Testing rig/carousel after modification
    </figcaption>
</figure>

We were able to get our hands on the carousel-like testing-bed at the [Robotics Institute](https://www.ri.cmu.edu/), the same that was used by the authors of this [paper](#references). After re-connecting some wires and playing around with the controls using an Arduino board, we were able to get it working. The rig was originally designed to test wheel performance on sand, which served as the default surface in all experiments.

The traction was characterised from the imprints created by the wheel in the sand.

The slipping study used data from wheel encoders which we had connected to the Arduino.

<image style="text-align: center;">
    <img src="images\wheel_testing.png">
    <figcaption style="text-align: center;">
        Figure 4: Our soft wheel being tested in deflated (left) and inflated (right) condition
    </figcaption>
</image>

## Publication

We wrote a paper on research outcomes of this class project (link will be available soon).

## References

$[1]$ Almusa, A., Galeza, R., Wang, M. and Majidi, C., 2020, May. Compliance-tuning soft inflatable wheels for robot mobility on various terrains. In 2020 3rd IEEE International Conference on Soft Robotics (RoboSoft) (pp. 558-563). IEEE.