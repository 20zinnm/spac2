target_include_directories(client PRIVATE ${CMAKE_CURRENT_LIST_DIR})

target_sources(client PRIVATE
        ${CMAKE_CURRENT_LIST_DIR}/Scene.h
        ${CMAKE_CURRENT_LIST_DIR}/SceneManager.h
        ${CMAKE_CURRENT_LIST_DIR}/Menu.h
        ${CMAKE_CURRENT_LIST_DIR}/Menu.cpp)