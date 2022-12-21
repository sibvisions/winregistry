Pur java registry wrapper

Registry reader/writter in Java without any additional dll. It uses the java.dll which is deliverd with any jre! Since version 3.0 it can also read/write DWORD, BINARY, MULTI and EXPAND entries! This functions use Runtime.exec() and the regedit exe!

This is a fork of https://code.google.com/archive/p/java-registry/

The library has been modified for compatibility with Java 11 and newer.


## Changes ##

- Eclipse project
- Simple ant build
- Support path names with spaces
