# About LH_Mouse

He is a Chinese C++, C and x86/x64 assembly programmer. Notwithstanding him being pedantic and misanthropic, his brilliantness has turned out to be priceless in both his work and contributions to the open source community. He takes semantical correctness as the primary goal, as well as efficiency and extensibility, with little regard to compatibility.

He is also one of the developers of the [mingw-w64](https://mingw-w64.org/) project.

![GNU nano for the win!](gnu-nano-ftw.png)

# His Projects

### Asteria (English)

![Watchers](https://img.shields.io/github/watchers/lhmouse/asteria.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/asteria.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/asteria.svg?style=plastic)

[Asteria](https://github.com/lhmouse/asteria) is a dynamically typed scripting language implemented in C++14. Its syntax looks similiar to JavaScript complemented by some extensions and rectification, and is hence pure [right regular grammar](https://en.wikipedia.org/wiki/Regular_grammar). It is also highly self-consistent for not discriminating [primitive types](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html) from class types. Instead, function arguments are passed by reference and the assignment operator (`=`, called the _assignment operator_ even in a definition such as `var i = 42`) always performs deep copying. It is also highly extensible and easy to integrate into existent C++ projects.

### mcfgthread (English)

![Watchers](https://img.shields.io/github/watchers/lhmouse/mcfgthread.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/mcfgthread.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/mcfgthread.svg?style=plastic)

[mcfgthread](https://github.com/lhmouse/mcfgthread) provides C++11 thread support for MinGW-w64 targets of GCC. Making use of undocumented Windows NT system calls directly, this library implements the most efficient mutexes and condition variables on Windows other than Microsoft's own ones, which are particularly the most ideal ones with the most comprehensive features and fewest overheads. He also builds [GCC with the MCF thread model](https://gcc-mcf.lhmouse.com/) constantly for public previews and tests.

### Poseidon (Chinese)

![Watchers](https://img.shields.io/github/watchers/lhmouse/poseidon.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/poseidon.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/poseidon.svg?style=plastic)

[Poseidon](https://github.com/lhmouse/poseidon) is a Linux-specific framework for server application development based on [coroutines](https://en.wikipedia.org/wiki/Coroutine). He has been contributing to this project throughout his work, as it is not only experimental, but for production environment, despite a few WIPs.

### MCF (Chinese)

![Watchers](https://img.shields.io/github/watchers/lhmouse/MCF.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/MCF.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/MCF.svg?style=plastic)

[MCF](https://github.com/lhmouse/MCF) is a Windows-specific C++17 framework. It is basically a large toy that consists of the minimal set of reinvented C and C++ wheels for daily use. It is a clean room design of the C and C++ [runtime library](https://en.wikipedia.org/wiki/Runtime_library).

### nano-win (English)

![Watchers](https://img.shields.io/github/watchers/lhmouse/nano-win.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/nano-win.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/nano-win.svg?style=plastic)

[nano-win](https://github.com/lhmouse/nano-win) ports [the nano editor](https://www.nano-editor.org/) from Linux to Windows, which is the only editor he uses on Linux. The editor ported is statically linked against most libraries, resulting in a standalone executable that requires no third party DLL. It also accepts both `Alt` keys as `Meta` keys and reads `.nanorc` from the Windows user home directory. The project is actively updated as long as new versions become available from the upstream.
