idf_component_register(
                         SRCS
                              "./main.c"
                              # "./Audio_Driver/PCM5101.c"
                              "./LCD_Driver/Vernon_ST7789T/Vernon_ST7789T.c"
                              "./LCD_Driver/ST7789.c"
                              "./Touch_Driver/esp_lcd_touch/esp_lcd_touch.c"
                              "./Touch_Driver/CST328.c"
                              "./LVGL_Driver/LVGL_Driver.c"
                              "./LVGL_UI/LVGL_Example.c"
                              # "./LVGL_UI/LVGL_Music.c"
                              "./SD_Card/SD_MMC.c"
                              "./I2C_Driver/I2C_Driver.c"
                              "./PCF85063/PCF85063.c"
                              "./QMI8658/QMI8658.c"
                              "./BAT_Driver/BAT_Driver.c"
                              "./PWR_Key/PWR_Key.c"
                              "./Wireless/Wireless.c"

                         INCLUDE_DIRS
                              # "./Audio_Driver"
                              "./LCD_Driver/Vernon_ST7789T"
                              "./LCD_Driver"
                              "./Touch_Driver/esp_lcd_touch"
                              "./Touch_Driver"
                              "./LVGL_Driver"
                              "./LVGL_UI"
                              "./SD_Card"
                              "./I2C_Driver"
                              "./PCF85063"
                              "./QMI8658"
                              "./BAT_Driver"
                              "./PWR_Key"
                              "./Wireless"
                              "."
                       )
