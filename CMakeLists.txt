project(rvs_laboratories_1)

find_package(CUDA REQUIRED)

add_executable(dataset_generator rvs_laboratories_1/dataset_generator.cpp)
cuda_add_executable(rvs_laboratories_1 rvs_laboratories_1/main.cu)
