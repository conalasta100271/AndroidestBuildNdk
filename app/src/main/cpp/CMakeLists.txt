cmake_minimum_required(VERSION 3.6.0)

add_library(includes/libyuv SHARED
            includes/libyuv.h)

# Include libraries needed for includes lib
target_link_libraries(includes/libyuv
                      android
                      log)