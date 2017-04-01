# About LH_Mouse

He is a Chinese C++, C and x86/x64 assembly programmer. Notwithstanding him being pedantic and misanthropic, his brilliantness has turned out to be priceless in both his work and contributions to the open source community. He takes semantical correctness as the primary goal, as well as efficiency and extensibility, with little regard to compatibility.

He is also one of the developers of the [mingw-w64](https://mingw-w64.org/) project.

# His Projects

## MCF (Chinese)

![Watchers](https://img.shields.io/github/watchers/lhmouse/MCF.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/MCF.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/MCF.svg?style=plastic)

[MCF](https://github.com/lhmouse/MCF) is a Windows-specific C++17 framework. It is basically a large toy that consists of the minimal set of reinvented C and C++ wheels for daily use. It is a clean room design of the C and C++ [runtime library](https://en.wikipedia.org/wiki/Runtime_library).

## mcfgthread (English)

![Watchers](https://img.shields.io/github/watchers/lhmouse/mcfgthread.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/mcfgthread.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/mcfgthread.svg?style=plastic)

[mcfgthread](https://github.com/lhmouse/mcfgthread) provides C++11 thread support for MinGW-w64 targets of GCC. Making use of undocumented Windows NT system calls directly, this library implements the most efficient mutexes and condition variables on Windows other than Microsoft's own ones, which are particularly the most ideal ones with the most comprehensive features and fewest overheads. He also constantly builds [GCC with mcfgthread support](http://www.lhmouse.com/gcc-mcf/) for public previews and tests.

## poseidon (Chinese)

![Watchers](https://img.shields.io/github/watchers/lhmouse/poseidon.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/poseidon.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/poseidon.svg?style=plastic)

[poseidon](https://github.com/lhmouse/poseidon) is a Linux-specific framework for server application development based on [coroutines](https://en.wikipedia.org/wiki/Coroutine). He contributes to this project throughout his work, as it is not only experimental, but for production environment, despite a few WIPs.

## nano-win (English)

![Watchers](https://img.shields.io/github/watchers/lhmouse/nano-win.svg?style=plastic) ![Stars](https://img.shields.io/github/stars/lhmouse/nano-win.svg?style=plastic) ![Forks](https://img.shields.io/github/forks/lhmouse/nano-win.svg?style=plastic)

[nano-win](https://github.com/lhmouse/nano-win) ports [the nano editor](https://www.nano-editor.org/) from Linux to Windows, which is the only editor he uses on Linux. The ported editor is statically linked against most libraries, resulting in a standalone executable that requires no third party DLLs. It also accepts both `Alt` keys as `Meta` keys and reads `.nanorc` from the Windows user home directory. The project is actively updated as long as new versions become available from the upstream.
