# crud_server.cc: a simple CRUD REST API server
a simple CRUD REST API server based on Pistache  and  nlohmann JSON library.
Pistache: https://github.com/oktal/pistache
nlohmann JSON: https://github.com/nlohmann/json

How to Build:

Download, build and install Pistache:
```
  git clone https://github.com/oktal/pistache.git
  cd pistache
  git submodule update --init
  mkdir build
  cd build
  cmake -G "Unix Makefiles" -DCMAKE_BUILD_TYPE=Release ..
  make
  sudo make install
```  
A simple way, just copy 'nlohmann/json.hpp' (from nlohmann JSON library /single_include/)  to C language header file directory of the system such as '/usr/local/include'

OR

Download, build and install Nlohmann JSON library:

```
  git clone https://github.com/nlohmann/json.git
  cd json
  mkdir build
  cd build
  cmake ..
  make
  sudo make install
```
  
  
