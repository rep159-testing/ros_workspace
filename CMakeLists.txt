cmake_minimum_required(VERSION 3.5)
project(ros_workspace NONE)

# The setup files in the root of the install prefix and the environment of
# the whole prefix come from ros_workspace_shell, which needs no ament
# package. This package adds the ament part on top of it: the
# AMENT_PREFIX_PATH hook for the prefix and the CMake config files, both
# installed by ament_package().
find_package(ament_cmake_core REQUIRED)

ament_package()
