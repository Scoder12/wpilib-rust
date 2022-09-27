# wpilib-rust

```sh
git submodule init --depth 1
mkdir build
cd build
cmake -DWITH_JAVA=OFF -DWITH_GUI=OFF -DWITH_CSCORE=OFF -B. -S../allwpilib/
cmake --build .
```
