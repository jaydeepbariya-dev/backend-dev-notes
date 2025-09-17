### Operating Systems for Backend Developers

## OS Fundamentals

What is an Operating System, purpose & functions

Types of Operating Systems (Batch, Multi-tasking, Real-time, Distributed)

Kernel vs User Space

System Calls (overview, purpose)

Processes vs Threads

--
## Processes & Threads

Process lifecycle: New → Ready → Running → Waiting → Terminated

Context switching (conceptual)

Thread vs Process (lightweight process)

Multithreading benefits for backend apps

Thread states, lifecycle, and scheduling basics

--
## Concurrency & Synchronization

Race conditions & critical section problem

Synchronization basics: mutex, semaphore, locks

Deadlocks: conditions and simple prevention strategies

Volatile, Atomic operations, Inter-thread communication (wait/notify)

--
## Memory Management

Memory types: Heap, Stack, Data, Code segments

Virtual memory & paging (conceptual)

Memory allocation basics

Garbage collection (JVM relevance)

--
## File Systems & I/O

File system concepts: files, directories, permissions

File descriptors & handles

Blocking vs Non-blocking I/O

Buffered vs Unbuffered I/O

Network I/O basics (sockets)

--
## CPU Scheduling & Performance

Scheduling algorithms overview: FCFS, SJF, Round-Robin

CPU-bound vs I/O-bound processes

Load balancing concepts for backend systems

Thread pools & ExecutorService relevance

--
## Networking Basics (OS perspective)

TCP vs UDP (conceptual)

Ports, sockets, IP addressing

OS role in handling connections & network I/O

--
## OS in Backend Systems

How OS supports:

Multithreading & concurrency in backend apps

Networking & socket handling

File I/O for logging, reading/writing data

Process isolation for microservices

JVM & OS interaction: memory, threads, garbage collection
