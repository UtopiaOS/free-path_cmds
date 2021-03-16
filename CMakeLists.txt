project(free-file_cmds)

cmake_minimum_required(VERSION 3.16)

add_utopia_binary(pathchk pathchk/pathchk.c)
add_utopia_binary(realpath realpath/realpath.c)