cmake_minimum_required(VERSION 2.8.9)
set (CMAKE_MODULE_PATH .)
project (usb-video-formatting)
find_package(libusb-1.0)


add_executable(usb-video-formatting src/main.cpp)
target_link_libraries(usb-video-formatting ${LIBUSB_1_LIBRARIES})


