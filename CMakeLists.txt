cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Plantower_PMS7003.h" "Plantower_PMS7003.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino)

project(Plantower_PMS7003)