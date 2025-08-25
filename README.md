# 🖥️ [MIT6.S081](https://pdos.csail.mit.edu/6.828/2021/schedule.html)

## 📚 Overview

This repository contains my solutions and notes for MIT's 6.S081 Operating System Engineering course, offered in the Fall of 2021. This course provides a deep dive into the design and implementation of operating systems, covering fundamental concepts such as virtualization, concurrency, and persistence. Through a series of challenging labs, students gain hands-on experience building a functional operating system kernel.

## 🗂️ Course Structure

The course is structured around a series of lectures, readings, and lab assignments. The lectures cover the theoretical foundations of operating systems, while the readings provide further details and insights. The lab assignments are designed to reinforce the concepts learned in the lectures and readings, and to provide practical experience in building an operating system.

Key topics covered in the course include:

*   **Virtualization:**  Understanding how operating systems create the illusion of multiple virtual machines on a single physical machine.  This includes concepts like virtual memory, process isolation, and system calls.
*   **Concurrency:**  Managing multiple tasks or threads executing simultaneously.  Topics include threads, locks, synchronization primitives, and deadlock avoidance.
*   **Persistence:**  Storing data reliably and durably, even in the face of system failures.  This involves file systems, disk management, and crash recovery.
*   **Networking:** Basic networking concepts are introduced.

## 🛠️ Building and Running xv6

To build and run xv6, you will need the following tools:

*   A RISC-V toolchain
*   QEMU (a machine emulator)

Please refer to the MIT 6.S081 website for detailed instructions on how to set up your development environment.

To build xv6, run the following command in the `xv6-riscv/` directory:

```bash
make
```

To run xv6 in QEMU, run the following command:

```bash
make qemu
```

## 📝 Notes and Observations

Throughout the course, I have made several observations and learned valuable lessons about operating system design. Some of these include:

*   The importance of careful design and planning before implementing any code.
*   The challenges of debugging concurrent code.
*   The need for a deep understanding of the underlying hardware.
*   The trade-offs between different design choices.

## ⚠️ Disclaimer

This repository contains my solutions to the MIT 6.S081 lab assignments.  These solutions are provided for educational purposes only.  Please do not copy or distribute these solutions without permission.  I am not responsible for any consequences that may arise from the use of these solutions.

## 🙏 Acknowledgements

I would like to thank the MIT 6.S081 staff for providing an excellent course and for their support throughout the semester. I would also like to thank the xv6 community for providing a valuable resource for learning about operating systems.
