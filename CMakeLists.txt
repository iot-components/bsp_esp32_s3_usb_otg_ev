idf_component_register(SRCS "board_esp32s3_usb_otg_ev.c" "board_wifi.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES "esp_adc_cal" nvs_flash)
