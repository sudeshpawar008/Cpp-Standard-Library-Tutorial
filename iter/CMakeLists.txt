PROJECT( util )
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)

#add_subdirectory( src )

#SET (CMAKE_CXX_FLAGS_INIT "-std=c++0x")
add_definitions("-std=c++0x")
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_EXECUTABLE(itercategory1 itercategory1.cpp)
ADD_EXECUTABLE(advance1 advance1.cpp)
ADD_EXECUTABLE(distance1 distance1.cpp)
ADD_EXECUTABLE(iterswap1 iterswap1.cpp)
ADD_EXECUTABLE(reviter1 reviter1.cpp)
ADD_EXECUTABLE(reviter2 reviter2.cpp)
ADD_EXECUTABLE(reviter3 reviter3.cpp)
ADD_EXECUTABLE(reviter4 reviter4.cpp)
ADD_EXECUTABLE(backinserter1 backinserter1.cpp)
ADD_EXECUTABLE(frontinserter1 frontinserter1.cpp)
ADD_EXECUTABLE(inserter1 inserter1.cpp)
ADD_EXECUTABLE(ostreamiter1 ostreamiter1.cpp)
ADD_EXECUTABLE(istreamiter1 istreamiter1.cpp)
ADD_EXECUTABLE(advance2 advance2.cpp)
ADD_EXECUTABLE(assoiter1 assoiter1.cpp)

#target_link_libraries( main Test )
