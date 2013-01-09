cmake_minimum_required(VERSION 2.8)

project(OhShExascale NONE)

include(UseLATEX.cmake)

add_latex_document(OhShExascale.tex
  BIBFILES OhShExascale.bib
  IMAGE_DIRS images
  )
