idf_component_register(SRCS "nvm_ds.c" "vibglove.c" "ble_init.c"
	INCLUDE_DIRS "." 
	REQUIRES "bt" "nvs_flash" "spi_flash" "driver")
