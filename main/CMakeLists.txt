idf_component_register(SRCS "lcd_test.c" "sanslab_logo.c"
                    INCLUDE_DIRS "."
                    REQUIRES lvgl esp_lcd driver esp_timer freertos)
