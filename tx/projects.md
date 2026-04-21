
## Projects

### Complete

- [x] [No BSS](https://github.com/cipher0-dev/nobss) - A minimal amd64 ELF binary builder

### In Progress

- [ ] [High-performance Epoll based HTTP Fileserver](https://github.com/cipher0-dev/epoll-fileserver)

### Ideas

- [ ] Review and categorize the entire amd64 Linux syscall table.
  - [syscall table](https://syscalls.w3challs.com/?arch=x86_64)
- [ ] Write your own linear algebra library
  - Start with vectors, matricies, and then tensors
  - Implement standard operations dot products, addition, mat mul, etc
  - Work on performance optimization with ILP, SIMD, CUDA and other
    implementaions
  - Write test suite and benchmarks
  - Do it in C++ to leverage googletest and google benchmark
- [ ] Memory maps visualizer
  - "attach" to a running process.
  - Read maps from /proc/pid/maps
  - Draw memory from 0 low to ff.. high visualizing the entire memory address
    space.
  - Mark maps and known address ranges with different colors.
  - Zoom in and out, down to individual bytes. Everything is at scale.
  - Track memory updates in real time.
- [ ] Binary scanner for ROP gadgets
  - Linearly search through .text section, find ret bytes and work back until
    you hit byte sequences that consistently don't map to valid encodings.
    Output these to help with finding useful ROP gadgets.
- [ ] Build a high-performance HTTP fileserver based on io_uring
- [ ] Toy Shell
  - Learning objective would be to get more experience with clone/pipe/execve.
  - CC:APP has a lab for this so I might do this as part of that lab.
- [ ] Memory allocators
  - I already implemented a basic free list allocator using sbrk as part of
    reading K&R C. This would be a repo to implement other, more modern
    allocation strategies.
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
