Compiling and running chdkptp
===============================

    svn checkout http://subversion.assembla.com/svn/chdkptp/trunk chdkptp
    cd chdkptp
    cp config-sample-linux.mk config.mk
    make


NOTE: On FreeBSD, use the `config-sample-freebsd.mk` in this dir and run
`gmake`.

Run with:

    LUA_PATH=$PWD/lua/?.lua ./chdkptp





