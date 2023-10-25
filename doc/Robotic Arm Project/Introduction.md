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


## Path Planning

The robotic arm has three working modes for grasping targets in different areas.

<div align="center">
    <img src="area" width="300px" display="inline"> 
    <div>
        <p>working mode for different area</p>
    </div>
</div>

<div align="center">
    <img src="area1" width="300px" display="inline"> 
    <div>
        <p>working area 1</p>
    </div>
</div>

<div align="center">
    <img src="area2" width="300px" display="inline"> 
    <div>
        <p>working area 2</p>
    </div>
</div>

<div align="center">
    <img src="area3" width="300px" display="inline"> 
    <div>
        <p>working area 3</p>
    </div>
</div>

<div align="center">
    <img src="Error Rate" width="300px" display="inline"> 
    <div>
        <p>Success rate in different areas</p>
    </div>
</div>
