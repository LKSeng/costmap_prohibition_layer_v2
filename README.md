# costmap_prohibition_layer_v2
ROS-Package that implements a costmap layer to add prohibited areas to the costmap-2D by a user configuration. In particular, this fork attempts to reduce CPU consumption by storing the cells that are obstacles/prohibited in memory instead, i.e. processing vs. memory trade-off.

Build status of the *kinetic-devel* branch:
- Travis (Ubuntu Trusty): [![Build Status](https://travis-ci.org/rst-tu-dortmund/costmap_prohibition_layer.svg?branch=kinetic-devel)](https://travis-ci.org/rst-tu-dortmund/costmap_prohibition_layer)

