cmake_minimum_required(VERSION 3.0)

install(PROGRAMS git-gen-authors DESTINATION bin)
install(PROGRAMS git-new-version DESTINATION bin)
install(PROGRAMS git-apply-branch DESTINATION bin)
install(PROGRAMS git-gen-changelog DESTINATION bin)

add_subdirectory(repo-lint)