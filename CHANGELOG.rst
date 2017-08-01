^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rf2o_laser_odometry
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.1.0 (2017-08-01)
------------------
* reduced verbosity
* added installation rules
* fixed headers when publishing the TF transforms.
  It fixes a previous commit... -_-
* - New param to set the topic name where to publish the odometry
  - New param to set if tf transformations are published or not (usefull when comparing different odometries)
  - new option to set the initial pose of the robot (from another topic). This is useful for simulation when the robot spans at pose (X,Y).
  - New launch file with the added params
* Update README.md
* Merge pull request #2 from dronecrew/tf
  TF fixes.
* Fixes for cmake.
* TF fixes.
* Test
* copy from old "mapir_ros_sources"
* new repo for RF2O
* Create README.md
* Contributors: James Goppert, Javier G. Monroy, Procópio Stein, jgmonroy
