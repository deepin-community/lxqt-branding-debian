install(DIRECTORY
    .
    DESTINATION "/etc/xdg/pcmanfm-qt"
    COMPONENT Runtime
    PATTERN "CMake*"
    EXCLUDE PATTERN "cmake*"
    EXCLUDE PATTERN "Makefile" EXCLUDE
)
