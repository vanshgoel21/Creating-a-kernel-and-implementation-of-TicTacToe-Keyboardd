Developing an operating system kernel involves constructing the fundamental framework upon which an operating system operates. This component directly interfaces with a computer's hardware, facilitating essential functions for the execution of other software.

The initial step in OS development is crafting a bootloader in 16-bit assembly language, typically executed in real mode. Bootloaders serve as the initial program to run before any operating system loads. They are responsible for booting other operating systems, often tailored to specific OS requirements. Bootloaders typically choose a specific operating system to initiate and oversee its loading process into memory.

For this task, certain tools and resources are necessary on a GNU/Linux system, such as:

GNU Assembler (gas) for assembling assembly language files.
GNU Compiler Collection (GCC), a C compiler, available in various versions.
Xorriso, a utility for creating, manipulating, and loading ISO 9660 filesystem images.
grub-mkrescue, a tool for generating GRUB rescue images, which internally employs xorriso functionality to construct ISO images.
QEMU, a Quick EMUlator enabling the booting of kernels in a virtual machine without necessitating a system reboot.
In terms of coding, the primary objective when starting from scratch is often to display content on the screen. This typically involves interacting with VGA (Visual Graphics Array), the hardware responsible for controlling display output.
*Implementation *

TicTacToe & Keyboard 
