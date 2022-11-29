# CMakeList.txt: проект CMake для 3semProject; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#
cmake_minimum_required (VERSION 3.8)

project ("3semProject")

# Добавьте источник в исполняемый файл этого проекта.
add_executable (3semProject "3semProject.cpp" "3semProject.h")

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
