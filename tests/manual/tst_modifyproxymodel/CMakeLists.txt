cmake_minimum_required(VERSION 3.10)
project(tst_modifyproxymodel_mnl VERSION 1.0.0)

set(PRODUCTNAME "tst_modifyproxymodel_mnl")
set(DESCRIPTION "tst_modifyproxymodel_mnl")
set(COMPANY     "RTPTechGroup")
set(COPYRIGHT   "Copyright (C) RTPTechGroup")
set(LIBRARIES
    treexmlmodel
)
include(../manual.cmake)

find_package(Qt5Core)
target_link_libraries(${PROJECT_NAME} Qt5::Core)

find_package(Qt5Widgets)
target_link_libraries(${PROJECT_NAME} Qt5::Widgets)

find_package(Qt5Sql)
target_link_libraries(${PROJECT_NAME} Qt5::Sql)
