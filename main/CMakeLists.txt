idf_component_register(SRCS "main.c" "rgb_led.c" "wifi_app.c" "http_server.c" "DHT22.c" "app_nvs.c" "wifi_resset_button.c"
                        EMBED_FILES "webpage/app.css" "webpage/app.js" "webpage/favicon.ico" "webpage/index.html" "webpage/jquery-3.3.1.min.js"
                       INCLUDE_DIRS ".")
