# CoreClrHelloWorld

Run on Mac
* runtime_mac/corerun app/HelloWorld.exe mac

Run on Linux
* runtime_linux/corerun app/HelloWorld.exe linux

Compile on Mac/Linux
* mcs -r:compile_r_lib/System.Console.dll -r:compile_r_lib/System.Runtime.dll -r:compile_r_lib/mscorlib.dll -nostdlib+ app/HelloWorld.cs