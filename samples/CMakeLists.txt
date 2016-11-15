add_executable(client_basic client_basic.c)
target_link_libraries(client_basic bearssl)

add_executable(server_basic server_basic.c)
target_link_libraries(server_basic bearssl)

