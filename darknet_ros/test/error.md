error:
-- Configuring done
CMake Error at /usr/share/cmake-3.10/Modules/FindCUDA.cmake:1801 (add_library):
  Cannot find source file:

    /data/ros/yue_ws_2020/src/darknet_ros/darknet/src/cuda.c

  Tried extensions .c .C .c++ .cc .cpp .cxx .m .M .mm .h .hh .h++ .hm .hp
sol:
${DARKNET_PATH}/src/dark_cuda.c

CMake Error at /usr/share/cmake-3.10/Modules/FindCUDA.cmake:1801 (add_library):
  Cannot find source file:

    /data/ros/yue_ws_2020/src/darknet_ros/darknet/src/logistic_layer.c

  Tried extensions .c .C .c++ .cc .cpp .cxx .m .M .mm .h .hh .h++ .hm .hpp
  .hxx .in .txx
Call Stack (most recent call first):
  darknet_ros/darknet_ros/CMakeLists.txt:145 (cuda_add_library)


  /data/ros/yue_ws_2020/src/darknet_ros/darknet_ros/include/darknet_ros/image_interface.h:16:30: error: unknown type name ‘IplImage’; did you mean ‘image’?
 void generate_image(image p, IplImage* disp);
                              ^~~~~~~~
                              image