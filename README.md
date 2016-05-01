# MikeOS-4.5_FAT32
This is the long awaited FAT32 version of MikeOS using The 1.44MB FAT32
Floppy Disk Image which makes a simple FAT32 driver as simple and easy
as FAT12. Say goodbye to FAT12 (and FAT16) and hello to FAT32.
See source\bootload\bootload.asm for the details on the new "format"
which is 100% compatible with the Microsoft FAT32 File System Specification.
Only minimal changes to the original source were required.
See MikeOS-4.5 FAT32 diff.txt for the details.

MikeOS is a 16-bit real mode operating system for x86-compatible PCs, 
written entirely in assembly language, which boots from a USB key.
It features a text-based dialog-driven user interface, a command-line,
support for FAT32 (MS-DOS-like) USB flash drive, sound (PC speaker),
text editor, BASIC interpreter and more.
The kernel includes over 60 system calls.

MikeOS is a learning tool for those wishing to understand simple OS 
construction and x86 assembly. Quick getting-started guide: MikeOS can 
run from a USB flash drive, either on an emulator or a real PC. 
See the disk_image/ directory for the files that you can write to the 
USB flash drive or boot in, for instance, VMware, QEMU or VirtualBox.

