cmake_minimum_required(VERSION 2.8)

install(
  PROGRAMS gen_cpp.py
  DESTINATION bin)

install(
  FILES msg.h.template srv.h.template
  DESTINATION share/gencpp
  )
