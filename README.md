## MDC Build Instructions

    cmake . -DARCH=ice40 -DICESTORM_INSTALL_PREFIX=$PWD/../icestorm/install -DCMAKE_INSTALL_PREFIX=$PWD/install
    make -j$(nproc)
    make install
