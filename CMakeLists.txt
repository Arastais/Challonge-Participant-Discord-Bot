# CMakeList.txt : CMake project for Challonge-Participant-Discord-Bot, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Challonge-Participant-Discord-Bot")

# Add source to this project's executable.
add_executable (Challonge-Participant-Discord-Bot "main.cpp" "main.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Challonge-Participant-Discord-Bot PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
