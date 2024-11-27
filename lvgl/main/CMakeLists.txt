idf_component_register(SRCS "main.c"
"components/lvgl/lvgl.c"
"components/lvgl/lv_demos.c"
"components/lvgl/lvgl_helpers.c"
                    INCLUDE_DIRS "."
                    "components/lvgl"
                    "components/lvgl_esp32_drivers")