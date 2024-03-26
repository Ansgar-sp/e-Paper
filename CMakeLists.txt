set(SOURCES
    ./src/EPD_7in5_V2.c
    ./src/font8.c
    ./src/font12.c
    ./src/font16.c
    ./src/DEV_Config.c
    ./src/dev_hardware_SPI.c
    ./src/GUI_Paint.c
    ./src/sysfs_gpio.c
    ./src/RPI_gpiod.c
    ./sysfs_software_spi.c
    )

idf_component_register(SRCS ${SOURCES}
                    INCLUDE_DIRS . inc
                    REQUIRES )