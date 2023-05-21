# Building on OSX for fsp-actorkit repo

    cmake . -DMBEDTLS_ROOT_DIR=../usr  -DNNG_ENABLE_TLS=ON -DCMAKE_INSTALL_PREFIX=../usr -G"Unix Makefiles"
    cmake --build . -j --target install --config Release

