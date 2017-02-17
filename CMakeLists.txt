cmake_minimum_required(VERSION 2.6)
project(redis)


AUX_SOURCE_DIRECTORY(./src REDIS_SRCS)

add_executable(redis ${REDIS_SRCS})
