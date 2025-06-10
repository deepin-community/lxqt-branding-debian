install(DIRECTORY
    .
    DESTINATION "/etc/xdg/xfce4"
    COMPONENT Runtime
    PATTERN "CMake*"
    EXCLUDE PATTERN "cmake*"
    EXCLUDE PATTERN "Makefile" EXCLUDE
)
