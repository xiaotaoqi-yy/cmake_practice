INCLUDE_DIRECTORIES(~/git/cmake_practice/backup/cmake/t3/build/install/include/hello)
LINK_DIRECTORIES(~/git/cmake_practice/backup/cmake/t3/build/install/lib)
ADD_EXECUTABLE(main main.c)
TARGET_LINK_LIBRARIES(main libhello.so)