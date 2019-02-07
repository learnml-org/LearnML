cmake_minimum_required(VERSION 3.8.0)
project(LearnML)

set(BUILD_LEARNML_CIS ON CACHE BOOL "")

if(${BUILD_LEARNML_CIS})
    add_subdirectory(./lml_cis)
endif()