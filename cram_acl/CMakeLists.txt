cmake_minimum_required(VERSION 2.8.3)
project(cram_acl)

find_package(catkin REQUIRED COMPONENTS
  roslisp
)

catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)
