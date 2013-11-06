cmake_minimum_required(VERSION 2.8.3)

project(test_nodelet_topic_tools)

find_package(catkin REQUIRED COMPONENTS message_filters nodelet nodelet_topic_tools pluginlib roscpp rostest)

catkin_package(
  CATKIN_DEPENDS message_filters nodelet nodelet_topic_tools pluginlib roscpp
)