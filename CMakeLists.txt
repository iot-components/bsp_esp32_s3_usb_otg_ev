idf_component_register(SRCS "bsp_esp32_s3_usb_otg_ev.c" "bsp_wifi.c"
                    INCLUDE_DIRS "include"
                    PRIV_REQUIRES "esp_adc_cal" nvs_flash)
