add_executable(point_cloud_main point_cloud_main.cpp)
target_link_libraries(point_cloud_main pointCloudUtil)
set_target_properties(point_cloud_main PROPERTIES LINK_FLAGS "-fopenmp")
