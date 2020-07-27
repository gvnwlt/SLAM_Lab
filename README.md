# SLAM_Lab

## A ROS Simulator Setup (Gazebo 9)
This is a simple ROS simulator setup complete with the launch files and sensor plugins you need so all you have to do is download this stuff and run it (or at least get things going with minimal configuration). You can run any bot with this, but I for the most part use 'janky_bot' in the simulator. Eventually I will be adding a bunch of different SLAM packages to test out. 

After cloning this repo, make sure the packages are installed: 

```
$ catkin_make 
$ rosrun slam_packages install_slam_packages.sh
```

### Heads Up 
* Right now I am in the process of getting the infrastructure in place, so expect some conflicts getting some of these SLAM packages to launch (I have a list of SLAM packages I plan to implement -- so on this first iteration I am only concerned with getting their launchers working a little and then doing the fine tuning on each of them on the next iterations).


### Updates
* Added gmapping, cartographer, rtabmap, hector-slam [2020-07-24]
* Added launches for 'slam_toolbox' [2020-07-26]
* Changed lua for Cartographer 2D [2020-07-26]

### Working On 
* Launching Karto SLAM 
