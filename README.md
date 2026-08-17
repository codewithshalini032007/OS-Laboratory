
# Operating Systems Laboratory

This repository contains the programs and implementations performed as part of the **Operating Systems Laboratory**.

## List of Experiments

| No. | Experiment                                    | Program File           |
| --- | --------------------------------------------- | ---------------------- |
| 1   | Basics of Unix Commands                       | `commands.txt`         |
| 2   | System Calls of Unix                          | `system_calls.c`       |
| 3   | Simulate Unix Commands                        | `simulate_commands.c`  |
| 4   | Shell Programming                             | `shell_program.sh`     |
| 5   | CPU Scheduling                                | `cpu_scheduling.c`     |
| 6   | Implement Semaphores                          | `semaphore.c`          |
| 7   | Shared Memory and IPC                         | `shared_memory.c`      |
| 8   | Banker's Algorithm for Deadlock Avoidance     | `bankers_algorithm.c`  |
| 9   | Algorithm for Deadlock Detection              | `deadlock_detection.c` |
| 10  | Threading & Synchronization Applications      | `threading.c`          |
| 11  | Memory Allocation Methods for Fixed Partition | `fixed_partition.c`    |
| 12  | Paging Technique of Memory Management         | `paging.c`             |
| 13  | Page Replacement Algorithms                   | `page_replacement.c`   |
| 14  | File Organization Techniques                  | `file_organization.c`  |
| 15  | File Allocation Strategies                    | `file_allocation.c`    |

---

## 1. Basics of Unix Commands

### Aim

To study and execute basic Unix/Linux commands.

### Commands Covered

* `pwd` – Display present working directory
* `ls` – List files and directories
* `mkdir` – Create a directory
* `cd` – Change directory
* `touch` – Create a file
* `cat` – Display file contents
* `cp` – Copy files
* `mv` – Move or rename files
* `rm` – Remove files
* `rmdir` – Remove directories
* `clear` – Clear terminal
* `whoami` – Display current user
* `date` – Display date and time
* `wc` – Count lines, words and characters
* `man` – Display command manual

### Result

Basic Unix commands were studied and executed successfully.

---

## 2. System Calls of Unix

### Aim

To implement and study basic Unix system calls.

### System Calls Used

* `fork()`
* `getpid()`
* `getppid()`
* `wait()`

### Compilation

```bash
gcc system_calls.c -o system_calls
```

### Execution

```bash
./system_calls
```

### Result

Basic Unix system calls were implemented and executed successfully.

---

## 3. Simulate Unix Commands

### Aim

To simulate basic Unix commands using a C program.

### Commands Simulated

* `ls`
* `cat`
* `cp`
* `wc`

### Compilation

```bash
gcc simulate_commands.c -o simulate_commands
```

### Execution

```bash
./simulate_commands
```

### Result

Basic Unix commands were simulated successfully using C.

---

## 4. Shell Programming

### Aim

To write and execute a shell script using Bash.

### Operations

* Display date
* Display current directory
* Display logged-in user
* List files
* Exit

### Execution

```bash
chmod +x shell_program.sh
./shell_program.sh
```

### Result

A menu-driven shell program was created and executed successfully.

---

## 5. CPU Scheduling

### Aim

To implement CPU scheduling algorithms.

### Algorithms

* First Come First Serve (FCFS)
* Shortest Job First (SJF)
* Round Robin

### Compilation

```bash
gcc cpu_scheduling.c -o cpu_scheduling
```

### Execution

```bash
./cpu_scheduling
```

### Result

CPU scheduling algorithms were implemented successfully.

---

## 6. Implement Semaphores

### Aim

To implement semaphores for process synchronization using the Producer-Consumer problem.

### Concepts

* Semaphore
* Mutex
* Producer
* Consumer
* Critical Section

### Compilation

```bash
gcc semaphore.c -o semaphore -pthread
```

### Execution

```bash
./semaphore
```

### Result

Semaphores were implemented successfully for process synchronization.

---

## 7. Shared Memory and IPC

### Aim

To implement Inter-Process Communication using shared memory.

### Concepts

* Shared Memory
* `shmget()`
* `shmat()`
* `shmdt()`
* `shmctl()`
* `fork()`

### Compilation

```bash
gcc shared_memory.c -o shared_memory
```

### Execution

```bash
./shared_memory
```

### Result

Inter-Process Communication using shared memory was implemented successfully.

---

## 8. Banker's Algorithm for Deadlock Avoidance

### Aim

To implement Banker's Algorithm for deadlock avoidance.

### Concepts

* Allocation Matrix
* Maximum Matrix
* Need Matrix
* Available Resources
* Safe Sequence

### Compilation

```bash
gcc bankers_algorithm.c -o bankers_algorithm
```

### Execution

```bash
./bankers_algorithm
```

### Result

Banker's Algorithm was implemented successfully to determine whether the system is in a safe state.

---

## 9. Deadlock Detection Algorithm

### Aim

To implement an algorithm for detecting deadlock in a system.

### Concepts

* Allocation Matrix
* Request Matrix
* Available Resources
* Work Vector
* Finish Vector

### Compilation

```bash
gcc deadlock_detection.c -o deadlock_detection
```

### Execution

```bash
./deadlock_detection
```

### Result

The deadlock detection algorithm was implemented successfully to identify whether deadlock exists.

---

## 10. Threading and Synchronization Applications

### Aim

To implement threads and synchronization using mutex.

### Concepts

* Threads
* `pthread_create()`
* `pthread_join()`
* Mutex
* Critical Section

### Compilation

```bash
gcc threading.c -o threading -pthread
```

### Execution

```bash
./threading
```

### Sample Output

```text
Final Counter Value: 200000
```

### Result

Threading and synchronization were implemented successfully using POSIX threads and mutex.

---

## 11. Memory Allocation Methods for Fixed Partition

### Aim

To implement memory allocation using fixed partitioning.

### Concepts

* Fixed Partitioning
* Memory Allocation
* Internal Fragmentation

### Compilation

```bash
gcc fixed_partition.c -o fixed_partition
```

### Execution

```bash
./fixed_partition
```

### Result

Memory allocation using fixed partitions was implemented successfully.

---

## 12. Paging Technique of Memory Management

### Aim

To implement the paging technique of memory management.

### Concepts

* Pages
* Frames
* Page Table
* Logical Address
* Physical Address

### Compilation

```bash
gcc paging.c -o paging
```

### Execution

```bash
./paging
```

### Result

The paging technique of memory management was implemented successfully.

---

## 13. Page Replacement Algorithms

### Aim

To implement page replacement algorithms used in memory management.

### Algorithms

* FIFO (First In First Out)
* LRU (Least Recently Used)

### Compilation

```bash
gcc page_replacement.c -o page_replacement
```

### Execution

```bash
./page_replacement
```

### Result

Page replacement algorithms were implemented successfully and page faults were calculated.

---

## 14. File Organization Techniques

### Aim

To implement basic file organization and record storage using C.

### Concepts

* File Handling
* Sequential File Organization
* `fwrite()`
* `fread()`
* Binary File

### Compilation

```bash
gcc file_organization.c -o file_organization
```

### Execution

```bash
./file_organization
```

### Result

File organization and record storage were implemented successfully using C file handling.

---

## 15. File Allocation Strategies

### Aim

To implement different file allocation strategies used in operating systems.

### Strategies

* Contiguous Allocation
* Linked Allocation
* Indexed Allocation

### Compilation

```bash
gcc file_allocation.c -o file_allocation
```

### Execution

```bash
./file_allocation
```

### Result

Different file allocation strategies were implemented successfully.

---

## Requirements

* Linux / Ubuntu
* GCC Compiler
* Bash Shell
* POSIX Threads

## How to Compile

For C programs:

```bash
gcc filename.c -o output
```

For programs using threads:

```bash
gcc filename.c -o output -pthread
```

For shell programs:

```bash
chmod +x filename.sh
./filename.sh
```

## Conclusion

All the above Operating Systems laboratory programs were implemented and tested successfully. The experiments cover **Unix commands, system calls, shell programming, CPU scheduling, synchronization, IPC, deadlock management, memory management, paging, page replacement, and file management techniques**.
