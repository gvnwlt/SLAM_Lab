# SLAM Packages 

## Ignored Packages Directory 
This directory contains all of the configured (or to be configured) SLAM packages for this project. The 'ignored_packages' directory contains a 'CATKIN_IGNORE' file to ignore these durning the build, so one can just select a package they want to build whenever to simply the build (once I figure out how -- I will streamline this process to selectively build). 

## Inside the SLAM Packages 
With each SLAM package will be a 'README' explaining what changes have been made and how to configure or use the package with the janky_simulator. 

## Compiling SLAM Packages
Refer to each packages respective 'README' that describes how to compile the package. In most cases 'catkin_make_isolated --install --use-ninja' should be used. 