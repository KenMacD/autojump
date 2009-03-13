cmake_minimum_required(VERSION 2.6)
project (autojump)

install (PROGRAMS autojump DESTINATION bin)
install (FILES autojump.1 DESTINATION share/man/man1)

install (CODE "message (STATUS \"
	Autojump installed to ${CMAKE_INSTALL_PREFIX}/bin.
	To complete installation source automake in your .bashrc.
\")")


