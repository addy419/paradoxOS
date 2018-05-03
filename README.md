# ParadoxOS
Unix unlike operating system. 

This is an hobbyst Operating System Project.

## Tools

* [Freestanding toolchain](https://wiki.osdev.org/GCC_Cross-Compiler) ( will make an automated script soon)
* GNU Make
* Grub
* qemu
* Linux (Obviously)

## Compiling Freestanding Toolchain
Execute the script `toolchain.sh`

## How to build

Once you have the requried tools. Simply fo to the project root and
```
    $ ./setup.sh iso
```

Then run the iso using qemu

```
    $ qemu-system-i686 -cdrom paradoxOS.iso
```
## Contributing

Contributinos are always welcome. Please check issues to see any pending task.

Feel free to send a pull request.