recrmdir
========

This little tool is a quick way to clean a directory tree: it will remove all empty directories

Features:

- fast

When & Why You Want To Use This Tool
------------------------------------

If you want to clean large directory trees. Or when you just need a handy little command 
that's the equivalent of
  find _path_ -type d -exec rmdir "{}" \;


Supported Platforms
------------------

- UNIX (Linux, BSD, ...): a generic Makefile is provided and it should build without complaint anywhere where there's a gcc (GNU C) compiler araound.
- Wondows (Win32/64): a MSVC10 (Microsoft Visual Studio 2010) project is provided to build the recrmdir.exe tool
