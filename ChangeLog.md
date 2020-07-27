# Change Log

## [0.0.2] - 2020-07-26

### Added
- Added SLAM launch files to run for installed SLAM packages (instead of maintaing SLAM packages in this repo the user/developer can rely on the ROS repo for these packages to get the latest versions)
- Added SLAM package install script that use the apt/ROS repo to install the necessary dependencies  

### Changed

### Fixed
- Fixed Cartographer 2D launch (issue with 'pose_extrapolator' being used more than once)

### Issues 
- Hector SLAM not not launching consistently (have to launch this after gazebo and rviz launch for now...)

## [0.0.1] - 2020-07-25

### Added
- Added SLAM packages that are to be configured for this sim/lab environment 

### Changed
- Restructured repo to reflect this effort 

### Fixed

## [0.0.0] - 2020-07-24
 
### Added
   
### Changed
- Changed name of the repo from ros_simulator -> SLAM_Lab

### Fixed
