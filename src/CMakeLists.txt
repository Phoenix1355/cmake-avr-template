add_avr_executable(${PROJECT_NAME} main.cpp)
avr_target_include_directories(${PROJECT_NAME} PRIVATE ${PROJECT_SOURCE_DIR}/include)
