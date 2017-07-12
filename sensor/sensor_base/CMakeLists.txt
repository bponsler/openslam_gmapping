include_directories(./)
add_library(sensor_base SHARED sensor.cpp sensorreading.cpp)
install(TARGETS sensor_base DESTINATION lib)
