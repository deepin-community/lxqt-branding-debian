install(DIRECTORY
    .
    DESTINATION "/etc/xdg/lxqt"
    COMPONENT Runtime
    PATTERN "CMake*"
    EXCLUDE PATTERN "cmake*"
    EXCLUDE PATTERN "Makefile" EXCLUDE
)
