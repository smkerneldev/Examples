cmake_minimum_required(VERSION 2.6)

Project(FunctionTemplateSpecialization)

ADD_EXECUTABLE(FunctionTemplateSpecialization
FunctionTemplateSpecialization.cpp Point.cpp)

ADD_EXECUTABLE(Deduction Deduction.cpp)