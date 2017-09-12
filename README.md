# FOSS-1
free and open source software.
 Practical No:10    
 
Learn Linux Kernel with respect to:
a.	What is Linux Kernel ?
b.	Operating Model
c.	Licensing Model
d.	How development works  ?

                               
                                        Linux Kernel


a.	What is Linux Kernel ?:
•	The Linux kernel is a monolithic Unix-like computer operating system kernel. The Linux family of operating systems is based on this kernel and deployed on both traditional computer systems such as personal computers and servers, usually in the form of Linux distributions
b.	Operating Model:
•	Kernel is the core part of Linux. It is responsible for all major activities of this operating system. It consists of various modules and it interacts directly with the underlying hardware. Kernel provides the required abstraction to hide low level hardware details to system or application programs.
c.	Licensing Model:
•	Initially, Torvalds released Linux under a license which forbade any commercial use.This was changed in version 0.12 by a switch to the GNU General Public License (GPL).
•	The Linux kernel is licensed explicitly only under version 2 of the GPL,without offering the licensee the option to choose "any later version", which is a common GPL extension. There was considerable debate about how easily the license could be changed to use later GPL versions (including version 3), and whether this change is even desirable.

d.	How development works  ?:
•	Linux kernel development process currently consists of a few different main kernel “branches” and lots of different subsystem-specific kernel branches. These different branches are:
    main 4.x kernel tree
    4.x.y -stable kernel tree
   4.x -git kernel patches
   subsystem specific kernel trees and patches
  the 4.x -next kernel tree for integration tests
•	The kernel is written mostly in C, with some architecture-dependent parts written in assembly. A good understanding of C is required for kernel development. Assembly (any architecture) is not required unless you plan to do low-level development for that architecture. Though they are not a good substitute for a solid C education and/or years of experience, the following books are good for, if anything, reference:
1.	“The C Programming Language” by Kernighan and Ritchie [Prentice Hall]
2.	“Practical C Programming” by Steve Oualline [O’Reilly]
3.	“C: A Reference Manual” by Harbison and Steele [Prentice Hall]


