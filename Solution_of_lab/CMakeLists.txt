add_executable(LaboratoryOne lab_1.cpp)
target_include_directories(LaboratoryOne PUBLIC ../LibraryCPP)
target_link_libraries(LaboratoryOne PUBLIC LibraryCPP)

add_executable(LaboratoryTwo lab_2.cpp)
target_include_directories(LaboratoryTwo PUBLIC ../LibraryCPPTemplate)

add_executable(LaboratoryThree lab_3.cpp)
target_include_directories(LaboratoryThree PUBLIC ../LibraryCPPTemplate)

add_executable(LaboratoryFour lab_4.cpp)
target_include_directories(LaboratoryFour PUBLIC ../LibraryCPPTemplate)