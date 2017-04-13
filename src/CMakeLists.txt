#add_executable( main main.cpp )

find_package(CUDA REQUIRED)
include_directories(${CUDA_INCLUDE_DIRS})
CUDA_ADD_EXECUTABLE(test_cuda main.cpp test_cuda_fun.cu) 