# Learn Log

This repo tracks my learning. It contains notes and experiments from blog posts,
conference talks, books, documentation, etc that further my learning on various
computing related topics.

## Projects

### Active

- [ ] [High-performance Epoll based HTTP Fileserver](https://github.com/cipher0-dev/epoll-fileserver)

### Completed

### In the Queue

- [ ] Build a high-performance HTTP fileserver based on io_uring
- [ ] Toy Shell
  - Learning objective would be to get more experience with clone/pipe/execve.
  - CC:APP has a lab for this so I might do this as part of that lab.
- [ ] Memory allocators
  - I already implemented a basic free list allocator using sbrk as part of
    reading K&R C. This would be a repo to implement other, more modern
    allocation strategies.
- [ ] Review and categorize the entire amd64 Linux syscall table.
- [ ] Create a mini-Linux distro
  - Build the Linux kernel and busybox/mucl from source.
  - Learning objective would be to gain more experience with the kernel.
- [ ] Build a TUI for monitoring system performance with BPF tools
  - Prerequisite: BPF Performance Tools
- [ ] Build a basic sampling profiler for systems languages
- [ ] Build a local VM based Kubernetes cluster
  - Learning objective would be to gain more experinece with building my own
    clusters.
  - Also provides an initial platform for future home lab work.
- [ ] Socket programming in ASM
  - Write some toy socket programs in amd64 asm
- [ ] Linking CPython into a Zig program for low-overhead calling into popular
      python packages

## Books

### Active

- [ ] [Computer Systems](https://www.amazon.com/Computer-Systems-Programmers-Perspective-3rd/dp/013409266X) [[notes](https://github.com/cipher0-dev/csapp)]

### Completed

- [x] [The C Programming Language](https://www.amazon.com/Programming-Language-2nd-Brian-Kernighan/dp/0131103628) [[notes](https://github.com/cipher0-dev/knrc)]
- [x] [The Linux Programming Interface](https://man7.org/tlpi/) [[notes](https://github.com/cipher0-dev/tlpi)]
- [x] [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/)
- [x] [The Rust Programming Language](https://doc.rust-lang.org/book/)

### In the Queue

- [ ] [BPF Performance Tools](https://www.brendangregg.com/bpf-performance-tools-book.html)
- [ ] [Site Reliability Engineering](https://sre.google/books/)
- [ ] [The Site Reliability Workbook](https://sre.google/books/)
- [ ] [Cracking the Coding Interview](https://www.crackingthecodinginterview.com/)
- [ ] [Beyond Cracking the Coding Interview](https://www.beyondctci.com/)
- [ ] [Systems Performance](https://www.brendangregg.com/blog/2020-07-15/systems-performance-2nd-edition.html)
- [ ] [Learning Linux Binary Analysis](https://www.oreilly.com/library/view/learning-linux-binary/9781782167105/)
- [ ] [CUDA By Example](https://developer.nvidia.com/cuda-example)
- [ ] [Programming Massively Parallel Processors](https://www.amazon.com/Programming-Massively-Parallel-Processors-Hands/dp/0323912311)
- [ ] [Introduction to Algorithms](https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844)
- [ ] [Introduction to Linear Algebra](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232716)
- [ ] [Structure and Interpretation of Computer Programs](https://www.amazon.com/Structure-Interpretation-Computer-Programs-Engineering/dp/0262510871)
- [ ] [Programming Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)
- [ ] [Designing Machine Learning Systems](https://www.amazon.com/Designing-Machine-Learning-Systems-Production-Ready/dp/1098107969)
- [ ] [Hands-On Machine Learning](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646)
- [ ] [Data Science from Scratch](https://www.oreilly.com/library/view/data-science-from/9781492041122/)
- [ ] [R for Everyone](https://www.jaredlander.com/r-for-everyone/)
- [ ] [Modern C](https://www.manning.com/books/modern-c-third-edition)
- [ ] [Data-oriented design](https://www.amazon.com/Data-oriented-design-engineering-resources-schedules/dp/1916478700)
- [ ] [Crafting Interpreters](https://www.amazon.com/Crafting-Interpreters-Robert-Nystrom/dp/0990582930)
- [ ] [Compilers Principles, Techniques, and Tools](https://www.amazon.com/Compilers-Principles-Techniques-Tools-2008-01-01/dp/B019TMH9MQ)
- [ ] [SEI CERT C Coding Standard 2016](https://chenweixiang.github.io/docs/SEI_CERT_C_Coding_Standard_2016_Edition.pdf)

## Documentation

### Active

### Completed

### In the Queue

- [ ] [Beej's Quick Guide to GDB](https://beej.us/guide/bggdb/)
- [ ] [Zig Language Reference](https://ziglang.org/documentation/master/)
- [ ] [Python/C API Reference Manual](https://docs.python.org/3/c-api/)
- [ ] [Neovim](https://neovim.io/)
- [ ] [LazyVim](https://www.lazyvim.org/)
- [ ] [SRE Book Updates](https://sre.google/resources/book-update/)
- [ ] [Lua Reference Manual](https://www.lua.org/manual/)

## Courseware

### Active

- [ ] [Carnegie Mellon 15-213 - Introduction to Computer Systems](https://www.cs.cmu.edu/~213/) [[notes](https://github.com/cipher0-dev/csapp)]

### Completed

### In the Queue

- [ ] [Stanford CS149 - Parallel Computing](https://gfxcourses.stanford.edu/cs149/fall25)

## Papers

### Active

### Completed

### In the Queue

- [Dynamic Storage Allocation: A Survey and Critical Review](https://csapp.cs.cmu.edu/3e/docs/dsa.pdf)

## Blogs

### Active

### Completed

### In the Queue

- [ ] [The Development of the C Language](https://csapp.cs.cmu.edu/3e/docs/chistory.html)
- [ ] [The C10K problem](http://www.kegel.com/c10k.html)
- [ ] [What Every C Programmer Should Know About Undefined Behavior #1/3](https://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html)
- [ ] [What Every C Programmer Should Know About Undefined Behavior #2/3](https://blog.llvm.org/2011/05/what-every-c-programmer-should-know_14.html)
- [ ] [What Every C Programmer Should Know About Undefined Behavior #3/3](https://blog.llvm.org/2011/05/what-every-c-programmer-should-know_21.html)
- [ ] [C23: A Slightly Better C](https://news.ycombinator.com/item?id=39081948)

## Talks

### Active

### Completed

### In the Queue

- [ ] [Performance Analysis Methodology](https://www.youtube.com/watch?v=abLan0aXJkw) [[notes](...)]
- [ ] [CppCon 2014: Mike Acton "Data-Oriented Design and C++"](https://www.youtube.com/watch?v=rX0ItVEVjHc)
- [ ] [Andrew Kelley: A Practical Guide to Applying Data Oriented Design (DoD)](https://www.youtube.com/watch?v=IroPQ150F6c)

## Problem Sets

### Active

### Completed

### In the Queue

- [ ] [LeetCode](https://leetcode.com/)
- [ ] [getcracked](https://getcracked.io/)
- [ ] [Brilliant](https://brilliant.org/)
