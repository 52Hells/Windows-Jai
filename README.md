# Windows-Jai
A Junk free Windows bindings for Jai 

> **_NOTE:_**  There is a lot of breaking changes so i am going to include windows_layer.jai to the bindings in the future when the main windows.jai is ready.

so all you have to do is literally copy and paste the 2 files in the module folder 

flags used to trim the Windows.h file are  

```cpp
#define WIN32_LEAN_AND_MEAN
#define NOGDICAPMASKS
#define NOSYSCOMMANDS
#define NORASTEROPS
#define OEMRESOURCE
#define NOATOM
#define NOCOLOR
#define NODRAWTEXT
#define NOKERNEL
#define NOMEMMGR
#define NOMETAFILE
#define NOOPENFILE
#define NOSCROLL
#define NOSERVICE
#define NOSOUND
#define NOTEXTMETRIC
#define NOWH
#define NOCOMM
#define NOKANJI
#define NOHELP
#define NOPROFILER
#define NODEFERWINDOWPOS
#define NOMCX
#define NOMINMAX
#define NORPC
#define NOPROXYSTUB
#define NOIMAGE
#define NOTAPE
#define UNICODE // may disable this 
```