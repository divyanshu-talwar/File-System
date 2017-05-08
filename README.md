# Pseudo File System
A mock file system implemented in C.

## Contributors

 * [Divyanshu Talwar](https://github.com/divyanshu-talwar)
 * [Vedant Nanda](https://github.com/nvedant07)

## Filesystem storage architecture

 * Super block : <file_system_id>,<filesystem_name>,<number of inode blocks>,<number of data blocks>
 * Inode bitmap : a single string of 1's and 0's
 * Data bitmap : a single string of 1's and 0's
 * Inode block : 16 lines per block,1 Inode per line. <filename>,<block number>
 * Data block : 1 line per block. <line1>;<line2> and so on.