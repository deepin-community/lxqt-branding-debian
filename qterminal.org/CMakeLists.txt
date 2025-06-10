install(DIRECTORY
    .
    DESTINATION "/etc/xdg/qterminal.org"
    COMPONENT Runtime
    PATTERN "CMake*"
    EXCLUDE PATTERN "cmake*"
    EXCLUDE PATTERN "Makefile" EXCLUDE
)
