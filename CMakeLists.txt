add_executable(p main.cpp)
target_compile_features(p PRIVATE cxx_std_20)
find_package(fmt REQUIRED)
target_link_libraries(p PRIVATE fmt::fmt)
