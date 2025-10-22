cmake_minimum_required(VERSION 3.5)
project(turtlebot3_autorace_localization_eval)

find_package(ament_cmake REQUIRED)
find_package(rclpy REQUIRED)

install(
  PROGRAMS
    src/logger_node.py
  DESTINATION lib/${PROJECT_NAME}
)

ament_package()
