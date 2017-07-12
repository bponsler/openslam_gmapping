include_directories(./)
add_library(utils SHARED movement.cpp stat.cpp)
install(TARGETS utils DESTINATION lib)
