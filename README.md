# Autonoums-navigatation_simulatation
This is a ROS packackge built for the simulaltation of <a href="https://github.com/Blackcipher101/Autonoums-navigatation">autonoums navigatation</a>.

<p>Its built using the technoliges below</p>
<ul>
<li>ROS</li>
<li>Gazebo</li>
<li>URDF</li>
<li>Xacro</li>
</ul>

## ROS
<p>The Robot Operating System (ROS) is a flexible framework for writing robot software. It is a collection of tools, libraries, and conventions 
that aim to simplify the task of creating complex and robust robot behavior across a wide variety of robotic platforms.</p>

## Gazebo
<p>Robot simulation is an essential tool in every roboticist's toolbox. A well-designed simulator makes it possible to rapidly test 
algorithms, design robots, perform regression testing, and train AI system using realistic scenarios. Gazebo offers the ability to 
accurately and efficiently simulate populations of robots in complex indoor and outdoor environments. At your fingertips is a robust 
physics engine, high-quality graphics, and convenient programmatic and graphical interfaces.</p>

## UDRF
<p>Unified Robot Description Format (URDF), which is an XML format for representing a robot model. The code API of the parser has been through our review process and will remain backwards compatible in future releases.</p>


## Xacro
<p>Xacro (XML Macros) Xacro is an XML macro language. With xacro, you can construct shorter and more readable XML files by using macros that expand to larger XML expressions.</p>

### Funtionalaties
<ul>
<li>Obstacle avoidance</li>
<li>Path planning</li>
<li>Works with the website</li>
</ul>

#### Introduction 
To setup this project first setup a ROS package(<a href="http://wiki.ros.org/ROS/Tutorials/BuildingPackages">tutrioal</a>)
Then clone the repo in the /src folder and build excutables using 
```
catkin_make
```
Now run the commands
```
roslaunch gazebo_ros empty_world.launch
```
and the to spawn the robot
```
roslaunch m2wrdescription spawn.launch
```

to see it in Rviz
```
roslaunch m2wrdescription rviz.launch 
```
Now run it

Voila!!! Your robot has spawned...

