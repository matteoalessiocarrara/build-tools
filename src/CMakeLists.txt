cmake_minimum_required(VERSION 3.0)

install(PROGRAMS git-changelog DESTINATION bin)
install(PROGRAMS git-new-version DESTINATION bin)
install(FILES Makefile DESTINATION $ENV{HOME}/Templates)