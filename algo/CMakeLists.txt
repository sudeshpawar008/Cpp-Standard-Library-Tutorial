PROJECT( algo )
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)

#add_subdirectory( src )

#SET (CMAKE_CXX_FLAGS_INIT "-std=c++0x")
add_definitions("-std=c++0x")
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_EXECUTABLE(foreach1 foreach1.cpp)
ADD_EXECUTABLE(foreach2 foreach2.cpp)
ADD_EXECUTABLE(foreach3 foreach3.cpp)
ADD_EXECUTABLE(count1 count1.cpp)
ADD_EXECUTABLE(minmax1 minmax1.cpp)
ADD_EXECUTABLE(find1 find1.cpp)
ADD_EXECUTABLE(find2 find2.cpp)
ADD_EXECUTABLE(searchn1 searchn1.cpp)
ADD_EXECUTABLE(search1 search1.cpp)
ADD_EXECUTABLE(search2 search2.cpp)
ADD_EXECUTABLE(findend1 findend1.cpp)
ADD_EXECUTABLE(findof1 findof1.cpp)
ADD_EXECUTABLE(adjacentfind1 adjacentfind1.cpp)
ADD_EXECUTABLE(equal1 equal1.cpp)
ADD_EXECUTABLE(ispermutation1 ispermutation1.cpp)
ADD_EXECUTABLE(mismatch1 mismatch1.cpp)
ADD_EXECUTABLE(lexicocmp1 lexicocmp1.cpp)
ADD_EXECUTABLE(issorted1 issorted1.cpp)
ADD_EXECUTABLE(ispartitioned1 ispartitioned1.cpp)
ADD_EXECUTABLE(isheap1 isheap1.cpp)
ADD_EXECUTABLE(allanynone1 allanynone1.cpp)
ADD_EXECUTABLE(copy1 copy1.cpp)
ADD_EXECUTABLE(copy2 copy2.cpp)
ADD_EXECUTABLE(copy3 copy3.cpp)
ADD_EXECUTABLE(move1 move1.cpp)
ADD_EXECUTABLE(transform1 transform1.cpp)
ADD_EXECUTABLE(transform2 transform2.cpp)
ADD_EXECUTABLE(swapranges1 swapranges1.cpp)
ADD_EXECUTABLE(fill1 fill1.cpp)
ADD_EXECUTABLE(generate1 generate1.cpp)
ADD_EXECUTABLE(iota1 iota1.cpp)
ADD_EXECUTABLE(replace1 replace1.cpp)
ADD_EXECUTABLE(replace2 replace2.cpp)
ADD_EXECUTABLE(remove1 remove1.cpp)
ADD_EXECUTABLE(remove2 remove2.cpp)
ADD_EXECUTABLE(unique1 unique1.cpp)
ADD_EXECUTABLE(unique2 unique2.cpp)
ADD_EXECUTABLE(unique3 unique3.cpp)
ADD_EXECUTABLE(reverse1 reverse1.cpp)
ADD_EXECUTABLE(rotate1 rotate1.cpp)
ADD_EXECUTABLE(rotate2 rotate2.cpp)
ADD_EXECUTABLE(permutation1 permutation1.cpp)
ADD_EXECUTABLE(shuffle1 shuffle1.cpp)
ADD_EXECUTABLE(randomshuffle1 randomshuffle1.cpp)
ADD_EXECUTABLE(partition1 partition1.cpp)
ADD_EXECUTABLE(partitioncopy1 partitioncopy1.cpp)
ADD_EXECUTABLE(sort1 sort1.cpp)
ADD_EXECUTABLE(sort2 sort2.cpp)
ADD_EXECUTABLE(partialsort1 partialsort1.cpp)
ADD_EXECUTABLE(partialsort2 partialsort2.cpp)
ADD_EXECUTABLE(nthelement1 nthelement1.cpp)
ADD_EXECUTABLE(heap1 heap1.cpp)
ADD_EXECUTABLE(binarysearch1 binarysearch1.cpp)
ADD_EXECUTABLE(includes1 includes1.cpp)
ADD_EXECUTABLE(bounds1 bounds1.cpp)
ADD_EXECUTABLE(equalrange1 equalrange1.cpp)
ADD_EXECUTABLE(merge1 merge1.cpp)
ADD_EXECUTABLE(sorted1 sorted1.cpp)
ADD_EXECUTABLE(inplacemerge1 inplacemerge1.cpp)
ADD_EXECUTABLE(accumulate1 accumulate1.cpp)
ADD_EXECUTABLE(innerproduct1 innerproduct1.cpp)
ADD_EXECUTABLE(partialsum1 partialsum1.cpp)
ADD_EXECUTABLE(adjacentdiff1 adjacentdiff1.cpp)
ADD_EXECUTABLE(relabs1 relabs1.cpp)

#target_link_libraries( main Test )
