# putty
来源于“https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html”的最新版本0.70

## android pie:
  * CFLAGS='-Werror=strict-aliasing' LDFLAGS='-lc -pie -fPIE' ./unix/configure --host=arm-linux-androideabi --prefix=$PWD/inst --without-gtk && make clean all

