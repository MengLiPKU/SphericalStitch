project (stitch)
find_package(OpenCV REQUIRED PATHS "~/opencv3lib/share/" NO_DEFAULT_PATH)
add_executable(stitch stitch.cpp)
target_link_libraries(stitch ${OpenCV_LIBS})
cmake_minimum_required(VERSION 2.8)
