^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package grid_map_core
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Fixing buffer handling bug for circular and ellipse iterators.
* Added Eigen macro for bit-alignment (`#88 <https://github.com/ethz-asl/grid_map/issues/88>`_).
* Added default copy constructor and assign operator methods after the rule of five.
* Fixing build error on ROS Kinetic.
* Fixing return value in `getQuadrant` member function.
* Extend grid_map_cv unit test for transparent pixels/nan-values.
* Contributors: Peter Fankhauser, Sascha, Thomas Emter

1.4.2 (2017-01-24)
------------------
* Added linear interpolation method for data access.
* Increased efficiency for linear interpolation method.
* Addressing C++ compiler warnings.
* Contributors: Dominic Jud, Peter Fankhauser, Horatiu George Todoran

1.4.1 (2016-10-23)
------------------
* Improved line iterator with start and end positions.
* Added method to retrieve submap size for iterators.
* Improved transformation of images to color grid map layers.
* Fixing issues with order of include with Eigen (`#67 <https://github.com/ethz-asl/grid_map/issues/67>`_).
* Contributors: Peter Fankhauser, Dominic Jud

1.4.0 (2016-08-22)
------------------
* Added convenience function to convert a grid map to form with circular buffer at (0,0).
* Contributors: Peter Fankhauser

1.3.3 (2016-05-10)
------------------
* Release for ROS Kinetic.
* Contributors: Peter Fankhauser

1.3.2 (2016-05-10)
------------------

1.3.1 (2016-05-10)
------------------
* Cleanup up Eigen types as preparation for ROS Kinetic release.
* Contributors: Peter Fankhauser

1.3.0 (2016-04-26)
------------------
* Made the `isInside` checks `const`.
* Fixes polygon iterator bug when using moved maps.
* Added unit test for polygon iterator on a moved map.
* Added comment about size of the returning submap.
* Reduced test build warning.
* Contributors: Peter Fankhauser, Martin Wermelinger, Marcus Liebhardt

1.2.0 (2016-03-03)
------------------
* Improved efficiency for the Grid Map iterator (speed increase of 10x for large maps) (`#45 <https://github.com/ethz-asl/grid_map/issues/45>`_).
* New iterator_benchmark demo to exemplify the usage of the iterators and their computational performance (`#45 <https://github.com/ethz-asl/grid_map/issues/45>`_).
* Added new method to set the position of a grid map (`#42 <https://github.com/ethz-asl/grid_map/pull/42>`_).
* Added new move_demo to illustrate the difference between the `move` and `setPosition` method.
* Fixed behavior of checkIfPositionWithinMap() in edge cases (`#41 <https://github.com/ethz-asl/grid_map/issues/41>`_).
* Updated documentation for spiral and ellipse iterator, and iterator performance.
* const correctness for grid's getSubmap.
* Cleanup of arguments and return types.
* Contributors: Péter Fankhauser, Christos Zalidis, Daniel Stonier

1.1.3 (2016-01-11)
------------------

1.1.2 (2016-01-11)
------------------
* Should fix errors on build server regarding Eigen3 and visualization_msgs dependencies.

1.1.1 (2016-01-11)
------------------
* Changes to CMakeLists.txt to enable compatibility with Ubuntu Saucy.

1.1.0 (2016-01-08)
-------------------
* added installation instructions in CMakeLists
* new ellipse iterator tool
* general improvements and bugfixes

1.0.0 (2015-11-20)
-------------------
* release for Springer ROS Book Chapter
