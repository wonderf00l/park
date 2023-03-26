add_library(utils src/utils.cpp)
target_include_directories(utils PUBLIC include)
#PUBLIC - все executable которые линкуются с либой utils видят папку include с hpp
