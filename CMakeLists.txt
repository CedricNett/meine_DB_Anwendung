cmake_minimum_required(VERSION 3.10)

project(  CLI11-Demonstrator
          LANGUAGES CXX
          DESCRIPTION "Shows the integration of CLI11"
          HOMEPAGE_URL "http://vorlesung.nabla-b.engineering"
)

add_executable( ${PROJECT_NAME} "${CMAKE_CURRENT_SOURCE_DIR}/src/main.cc" )
