cmake_minimum_required(VERSION 3.8)
project(map_launch)

find_package(avyana_cmake REQUIRED)
avyana_package()

ament_auto_package(
  INSTALL_TO_SHARE
  launch
)
