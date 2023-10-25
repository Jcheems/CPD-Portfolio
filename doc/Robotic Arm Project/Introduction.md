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


Success rate in different areas

模型分隔分析需要进行一次全局的深度优先搜索。在未优化之前，采用的是递归的方式实现，但是因为需要搜索上百万个节点，因此出现了 StackOverflow。使用迭代改进之后，就不需要将一些数据压入递归栈中，基本不消耗内存。


