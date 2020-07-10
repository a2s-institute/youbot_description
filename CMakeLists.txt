cmake_minimum_required(VERSION 3.5)
project(youbot_description)

install(DIRECTORY controller/ DESTINATION share/${PROJECT_NAME}/controller)
install(DIRECTORY controller/ DESTINATION share/${PROJECT_NAME}/meshes)
install(DIRECTORY controller/ DESTINATION share/${PROJECT_NAME}/robots)
install(DIRECTORY controller/ DESTINATION share/${PROJECT_NAME}/urdf)
