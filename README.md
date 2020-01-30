Para compilar:

g++ -o Prueba Prueba.cpp glovehttpserver.cpp glove.cpp glovewebsockets.cpp glovecoding.cpp glovehttpcommon.cpp -lpthread -DENABLE_OPENSSL=0 -DENABLE_COMPRESSION=0 -std=c++11