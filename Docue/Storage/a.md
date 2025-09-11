# Storage

Secane Storage node that has not tool any byte data storage, 
has fold entry in its parent fold only, and none storage block alloc to its data storage.

Secane Storage path is case sensitive.

Secane Storage path is Utf-32 little endian without bom char list.

Secane Storage path count practic is 256.

Secane Storage path absolute start with colon.

Secane Storage unit is block.

Block size is 64 kilo byte.

Secane Storage not write when done read operate.

Secane Storage not write storage node last access time.

Secane Storage not write storage node time.

Module can write time info in separate file when done storage read and write.