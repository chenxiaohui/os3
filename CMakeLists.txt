PROJECT(os3)
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_LIBRARY(os3 STATIC ${DIR_SRCS})
