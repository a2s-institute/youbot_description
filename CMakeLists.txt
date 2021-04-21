cmake_minimum_required(VERSION 3.5)
project(youbot_description)

find_package(ament_cmake REQUIRED)

install(DIRECTORY controller/ DESTINATION share/${PROJECT_NAME}/controller)
install(DIRECTORY meshes/ DESTINATION share/${PROJECT_NAME}/meshes)
install(DIRECTORY robots/ DESTINATION share/${PROJECT_NAME}/robots)
install(DIRECTORY urdf/ DESTINATION share/${PROJECT_NAME}/urdf)

ament_package()
