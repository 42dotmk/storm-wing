add_executable(storm-wing main.cpp)

target_compile_features(storm-wing
  PRIVATE
    cxx_std_23
)

find_package(sparq CONFIG REQUIRED)

target_link_libraries(storm-wing 
  PRIVATE
    sparq::sparq
    sparq::sparqHal
    sparq::sparqPal
    sparq::sparqCommon
)
