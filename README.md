# weenix
A full operating system kernel, based on Unix, built as a semester-long project in CS 1670 at Brown University. More information about the course and the individual projects can be found on the [course website](https://brown-cs1690.github.io/brown-cs167-s24/).

The projects, in order of completion:
- **Procs**: Threads, processes, and synchronization primitives.
- **Drivers**: Device drivers for terminals, disks, and the memory devices `/dev/zero` and `/dev/null`.
- **VFS (Virtual File System**: A polymorphic interface between the operating system kernel and the various file systems (such as S5FS and device drivers).
- **S5FS (System V File System)**: A file system implementation based on the original Unix file system.
- **VM (Virtual Memory)**: Userspace address management, running user-level code, servicing system calls, and everything else needed to combine all the previous components into a fully functioning operating system. This includes virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls (in particular, the `fork` syscall).

NOTE: This is a placeholder repo with no code, to respect Brown's Academic Code. If you are a potential employer and would like to look at the code, please send me an email. 
