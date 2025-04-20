```
$ cmake ../source/
-- The CXX compiler identification is GNU 13.3.0
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Check for working CXX compiler: /usr/bin/c++ - skipped
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Configuring done (0.3s)
-- Generating done (0.0s)
-- Build files have been written to: /home/<PATH>/cmake_cheat_sheet/2-ch/build
$:~/Projects/cmake_cheat_sheet/2-ch/build$ ls
CMakeCache.txt  CMakeFiles  cmake_install.cmake  Makefile
$:~/Projects/cmake_cheat_sheet/2-ch/build$ cmake --build .
[ 25%] Building CXX object CMakeFiles/MyExe.dir/main.cpp.o
[ 50%] Linking CXX executable MyExe
[ 50%] Built target MyExe
[ 75%] Building CXX object CMakeFiles/Test.dir/test.cpp.o
[100%] Linking CXX executable Test
[100%] Built target Test
$ ls
CMakeCache.txt  CMakeFiles  cmake_install.cmake  Makefile  MyExe  Test
```