cmake_minimum_required(VERSION 3.0)
project ("VBacklight")

link_libraries(xcb-randr xcb-render xcb-util xcb ncurses)
add_executable(vbacklight vbacklight.cpp)
install(TARGETS vbacklight DESTINATION bin)