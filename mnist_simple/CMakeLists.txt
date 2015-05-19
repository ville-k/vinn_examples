add_executable(mnist_simple example_mnist.cpp)
target_include_directories(mnist_simple PRIVATE ViNN::ViNN)
target_compile_definitions(mnist_simple PRIVATE ViNN::ViNN)
target_link_libraries(mnist_simple LINK_PRIVATE ViNN::ViNN)
