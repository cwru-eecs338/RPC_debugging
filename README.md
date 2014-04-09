RPC_debugging
=============

RPC code which has been modified to be suitable for debugging


use the following command to compile:
    gcc -DDEBUG -g hello_client_gdb.c hello_server.c -o hello_gdb
    
Then, you can either use ./hello_gdb hostname to run this program 
or
use 
  gdb hello_gdb 
  to debug the program
 
    
    
