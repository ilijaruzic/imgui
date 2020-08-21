cmake_minimum_required(VERSION 3.8)
project(imgui)

add_library(imgui 
	imgui.h
	imconfig.h
	imgui_internal.h
	imstb_rectpack.h
	imstb_textedit.h
	imstb_truetype.h
	imgui.cpp
	imgui_demo.cpp
	imgui_draw.cpp
	imgui_widgets.cpp)
target_include_directories(imgui PUBLIC)
