^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rotors_control
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.1.0 (2017-04-08)
-----------
* Removing unfinished parts of px4 dummy controller and gazebo mavlink interface. Refactoring gazebo mavlink interface.
* set all queue lengths to 1
* make rotors_control CMakeLists consistent with upstream
* bring rotors_control CMakeLists closer to upstream
* update launch and xacro files to new names, update use of odometry plugin
* px4 dummy controller: fix include paths after merge
* fix include dir
* move px4 files to new directories
* Contributors: Fadri Furrer, Thomas Gubler, pvechersky

2.0.1 (2015-08-10)
------------------

2.0.0 (2015-08-09)
------------------
* Converted to new mav_comm messages, including new MultiDOFJointTrajectory and PoseStamped as waypoints.
* Added subscriber for MultiDOFJointTrajectory messages and extended waypoint_publisher_file to test it. resolves `#243 <https://github.com/ethz-asl/rotors_simulator/issues/243>`_
* Contributors: Helen Oleynikova, Markus Achtelik

1.1.6 (2015-06-11)
------------------

1.1.5 (2015-06-09)
------------------
* added install targets

1.1.4 (2015-05-28)
------------------

1.1.3 (2015-05-28)
------------------
* added installation of controller libraries

1.1.2 (2015-05-27)
------------------
* added nav_msgs dependency and fixed rotors_evaluation's setup.py

1.1.1 (2015-04-24)
------------------

1.1.0 (2015-04-24)
------------------
* initial Ubuntu package release
