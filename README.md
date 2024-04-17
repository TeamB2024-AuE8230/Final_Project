# Final_Project
## Installation
1. Use ``catkin_create_pkg`` to make package called turtlebot_autonav
2. Clone the repo to package directory, either directly or using symbolic links
3. Run ``catkin_make`` in your termnial.
4. Make sure to edit in ``parrot2.py`` and ``parrot2_gazebo.py`` line 11 to include your path to ``stop_sign_classifier_2.xml ``
5. Be sure to have run or added the following commands to your ``.bashrc`` and source it
   * ``export TURTLEBOT3_MODEL=burger``
   *  ``source devel/setup.bash
## Running the package
1. After installation, you can run ``roslaunch turtlebot_autonav turtle.launch `` or ``roslaunch turtlebot_autonav gazebo.launch `` to launch on physical Turtlebot or in Gazebo
