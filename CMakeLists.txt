add_library(DearImGui
        "${CMAKE_CURRENT_SOURCE_DIR}/imconfig.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/imgui.cpp"
        "${CMAKE_CURRENT_SOURCE_DIR}/imgui.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/imgui_demo.cpp"
        "${CMAKE_CURRENT_SOURCE_DIR}/imgui_draw.cpp"
        "${CMAKE_CURRENT_SOURCE_DIR}/imgui_internal.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/imgui_tables.cpp"
        "${CMAKE_CURRENT_SOURCE_DIR}/imgui_widgets.cpp"
        "${CMAKE_CURRENT_SOURCE_DIR}/imstb_rectpack.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/imstb_textedit.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/imstb_truetype.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/backends/imgui_impl_opengl3.cpp"
        "${CMAKE_CURRENT_SOURCE_DIR}/backends/imgui_impl_opengl3.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/backends/imgui_impl_opengl3_loader.h"
        "${CMAKE_CURRENT_SOURCE_DIR}/backends/imgui_impl_glfw.cpp"
        "${CMAKE_CURRENT_SOURCE_DIR}/backends/imgui_impl_glfw.h"
        )

include_directories(${CMAKE_CURRENT_SOURCE_DIR})
include_directories(${PROJECT_SOURCE_DIR}/include)
