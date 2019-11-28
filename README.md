# tbb_link_example

Example trying to reproduce an error where libtbbmalloc.so.2 cannot be found in the executable's rpath. 

Intel TBB libraries can be downloaded from https://www.nuget.org/packages/inteltbb.devel.linux/

The package's content can be unzipped using standard zip tools, and libraries and header files can be copied into the lib and include folders. 

cp -r inteltbb.devel.linux.2019.8.281/lib/native/include include
cp -r inteltbb.devel.linux.2019.8.281/lib/native/linux-x64/* lib
cp -r inteltbb.devel.linux.2019.8.281/runtimes/linux-x64/native
