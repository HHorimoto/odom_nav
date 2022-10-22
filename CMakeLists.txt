cmake_minimum_required(VERSION 3.0.2)
project(move_nav)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
)

catkin_package()