# db_converter-macos

Game archive packer/unpacker for the S.T.A.L.K.E.R. game series.  
Based on bardak's converter from xray_re-tools.

## Build
```
git clone https://github.com/elseform/db_converter-macos.git
cd db_converter
mkdir build
cd build
brew install boost cmake spdlog fmt lzo googletest dylibbundler
cmake ..
make -j$(sysctl -n hw.ncpu)
```