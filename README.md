rtmpdump-vs
===========

This is the rtmpdump utility (and librtmp) VisualStudio project.

Credits
-------
The rtmpdump code is taken from: svnpenn/rtmpdump repository on github.com

Compilation is made possible using getopt.c from MinGW.

How to setup
------------
1) Install the developer version of OpenSSL and ZLib.

2) Open the solution, it has 2 projects (librtmp & rtmpdump).

3) For EACH project, right-click -> Properties -> Configuration Properties -> VC++ Directories

   Under "Include Directories" change the path of the OpenSSL and ZLib to where you installed it.
   
   Under "Library Directories" change the path of the OpenSSL and ZLib to where you installed it.
   
4) Again, the above step should be done to both projects.


I am not a VC++ developer, so there might be an easier way to setup this solution, if you can think
of any feel free to share...
   
