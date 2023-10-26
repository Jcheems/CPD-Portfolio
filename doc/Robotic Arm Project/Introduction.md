# Project Design

The robotic arm grasping the object block mainly realizes two main functions, the image recognition function of the camera and the planning path function.

<div align="center">
    <img src="example.gif" width="300px" display="inline"> 
</div>

## Image Recognition

The position of the target is determined by comparing the template and the actual captured image.

<div align="center">
    <img src="template.jpg" width="100px" display="inline"> 
</div>

Target blocks at different angles

<div align="center">
    <img src="0.jpg" width="300px" display="inline"> 
    <div>
        <p>0°</p>
    </div>
</div>

<div align="center">
    <img src="30.jpg" width="300px" display="inline"> 
    <div>
        <p>30°</p>
    </div>
</div>

<div align="center">
    <img src="45.jpg" width="300px" display="inline"> 
    <div>
        <p>45°</p>
    </div>
</div>

<div align="center">
    <img src="60.jpg" width="300px" display="inline"> 
    <div>
        <p>60°</p>
    </div>
</div>

Image recognition of camera viewpoints

<div align="center">
    <img src="cognition.png" width="300px" display="inline"> 
    <div>
        <p></p>
    </div>
</div>

The red square box indicates the position of the target block after comparing the viewing angle with the template, which is the position that will be grasped.

## Path Planning

The robotic arm has three working modes for grasping targets in different areas.

<div align="center">
    <img src="area.png" width="300px" display="inline"> 
    <div>
        <p>working mode for different area</p>
    </div>
</div>

<div align="center">
    <img src="area1.jpg" width="300px" display="inline"> 
    <div>
        <p>working area 1</p>
    </div>
</div>

<div align="center">
    <img src="area2.jpg" width="300px" display="inline"> 
    <div>
        <p>working area 2</p>
    </div>
</div>

<div align="center">
    <img src="area3.jpg" width="300px" display="inline"> 
    <div>
        <p>working area 3</p>
    </div>
</div>

<div align="center">
    <img src="Error Rate.png" width="600px" display="inline"> 
    <div>
        <p>Success rate in different areas</p>
    </div>
</div>

## Coursework Report

More details please take a look at：<a href="https://github.com/Jcheems/Jcheems.github.io/blob/main/doc/Robotic%20Arm%20Project/Project_Report.pdf" target="_blank">Coursework Project.</a>
