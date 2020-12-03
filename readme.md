How to install LUA on Windows

https://www.lua.org/download.html


Install Lua.exe
Use SciTE IDE for writing code 

Add the paths in Environmental Variables

  PATH     :   C:\Program Files (x86)\LuaRocks
  PATHEXT  :   .LUA
LuaRocks;
  PATH     :   C:\Program Files (x86)\LuaRocks
  LUA_PATH :   C:\Program Files (x86)\LuaRocks\lua\?.lua;C:\Program Files (x86)\LuaRocks\lua\?\init.lua
Local user rocktree (Note: %APPDATA% is user dependent);
  PATH     :   %APPDATA%\LuaRocks\bin
  LUA_PATH :   %APPDATA%\LuaRocks\share\lua\5.1\?.lua;%APPDATA%\LuaRocks\share\lua\5.1\?\init.lua
  LUA_CPATH:   %APPDATA%\LuaRocks\lib\lua\5.1\?.dll
System rocktree
  PATH     :   C:\Program Files (x86)\LuaRocks\systree\bin
  LUA_PATH :   C:\Program Files (x86)\LuaRocks\systree\share\lua\5.1\?.lua;C:\Program Files (x86)\LuaRocks\systree\share\lua\5.1\?\init.lua
  LUA_CPATH:   C:\Program Files (x86)\LuaRocks\systree\lib\lua\5.1\?.
  
  
  
  
