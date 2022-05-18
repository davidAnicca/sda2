cmake_minimum_required(VERSION 3.21)
project(partial_recap_2)

set(CMAKE_CXX_STANDARD 14)

add_executable(partial_recap_2 main.cpp Gui.cpp Gui.h Procesor.cpp Procesor.h PlacaDeBaza.cpp PlacaDeBaza.h RepoProcesor.cpp RepoProcesor.h RepoPlacaDeBaza.cpp RepoPlacaDeBaza.h Service.cpp Service.h Tests.cpp Tests.h)
set(CMAKE_PREFIX_PATH "C:\\Qt\\6.2.4\\mingw_64\\lib\\cmake")
find_package(Qt6Widgets REQUIRED)
target_link_libraries(partial_recap_2 Qt6::Widgets)
