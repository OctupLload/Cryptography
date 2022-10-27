cmake_minimum_required(VERSION 3.23)
project(Cryptography)

set(CMAKE_CXX_STANDARD 14)

add_executable(Cryptography
        src/main/c/com/crypto/ciphers/atbash/Atbash.cpp
        src/main/c/com/crypto/ciphers/vigenere/Vigenere.cpp)
