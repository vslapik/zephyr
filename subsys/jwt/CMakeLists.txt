zephyr_link_interface_ifdef(CONFIG_MBEDTLS mbedTLS)
zephyr_library()
zephyr_library_sources(jwt.c)
zephyr_library_link_libraries_ifdef(CONFIG_MBEDTLS mbedTLS)
