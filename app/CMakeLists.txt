add_executable(run_mapping_online run_mapping_online.cc)
target_link_libraries(run_mapping_online
        ${GLOG_LIBRARY}
        ${PROJECT_NAME} gflags
        )
add_executable(run_mapping_offline run_mapping_offline.cc)
target_link_libraries(run_mapping_offline
        ${GLOG_LIBRARY}
        ${PROJECT_NAME} gflags
        )
