# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Reem Alyahya |
| **Student ID** | 445052108 |
| **University Email** | 445052108@std.psau.edu.sa |
| **GitHub Username** | ro500sy500-oss |
| **Repository Link** | https://github.com/ro500sy500-oss/OS-Assignment1-Reem-Alyahya |
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1tqI5TKPRGXdR2BdzdAK0jDJ6ZylhE8a4/view?usp=drivesdk

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 445052108` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

---

# Part A: Development Log (0.5 mark)

### Entry 1 - [October 7, 2026, 10:00 AM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Forked the starter repository and renamed it to OS-Assignment1-Reem-Alyahya
- Changed student ID on line 150 to my actual ID (445052108)
- Compiled and ran the initial program in NetBeans successfully

**Challenges**: Configuring the proper project paths and resolving initial NetBeans execution output tabs

**Solution**: Used Run File option directly on SchedulerSimulation.java to bypass main class conflicts

**Time spent**: 45 minutes

---

### Entry 2 - [October 8, 2026, 2:30 PM]
**What I did**: Implemented Feature 1 (Process Priority)

**Details**:
- Added a priority attribute ranging from 1 to 10 inside the Process class
- Integrated priority scheduling logic into the queue management structure

**Challenges**: Ensuring the priority value correctly affects process sorting and execution order

**Solution**: Updated the constructor and getter methods to accurately handle priority inputs

**Time spent**: 1 hour

---

### Entry 3 - [October 9, 2026, 11:15 AM]
**What I did**: Implemented Feature 2 (Context Switch Counter) and Feature 3 (Waiting Time Tracking)

**Details**:
- Created a static context switch counter variable to track every switch between threads
- Implemented waiting time and turnaround time calculation methods using system timestamps

**Challenges**: Accurately tracking context switches during live quantum preemption without double-counting

**Solution**: Incremented the counter explicitly inside the scheduler loop whenever the active thread yields control

**Time spent**: 1.5 hours

---

### Entry 4 - [October 10, 2026, 4:45 PM]
**What I did**: Recorded and uploaded the demonstration video

**Details**:
- Recorded a 3-minute video walkthrough covering code architecture, live execution, and features
- Uploaded the video to Google Drive and set sharing permissions to public view
- Pasted the shareable link into MY_WORK.md

**Challenges**: Keeping the video duration within the 2 to 3-minute limit while explaining all required components

**Solution**: Prepared a brief script highlighting the core classes, features, and terminal summary table

**Time spent**: 1 hour

---

### Entry 5 - [October 11, 2026, 8:00 PM]
**What I did**: Completed reflection, technical answers, and final documentation review

**Details**:
- Answered all questions in Part B (Reflection) and Part C (Technical Answers) in my own words
- Verified all requirements against the assignment README checklist
- Prepared the repository for final Blackboard submission

**Challenges**: Ensuring technical explanations accurately referenced specific methods from SchedulerSimulation.java

**Solution**: Re-read the source code from top to bottom to cite precise methods like Thread.start() and Thread.join()

**Time spent**: 1 hour

---

## Development Log Summary

**Total time spent on assignment**: 5.25 hours

**Most challenging part**: Managing thread synchronization and accurately capturing context switch counts during live quantum execution.

**Most interesting learning**: Gaining a deep practical understanding of how operating systems manage process scheduling, waiting queues, and CPU time allocation using Java concurrency.

**What I would do differently next time**: Start incremental commits even earlier across more scattered calendar dates.

---

# Part B: Reflection (0.5 mark)

## Question 1: What did you learn about multithreading?
Through this assignment, I learned how Java threads can be utilized to simulate concurrent operating system processes effectively. I gained hands-on experience implementing the `Runnable` interface and managing thread execution using `Thread.start()`. Controlling thread lifecycles with `Thread.sleep()` helped me understand how CPU bursts are simulated in software environments. Furthermore, observing `Thread.join()` in action clarified how a main scheduler thread waits for all simulated processes to complete their execution cycles. It was fascinating to see how multiple threads interact within a shared memory space while maintaining independent execution states.

## Question 2: What was the most challenging part of this assignment?
The most challenging part of this assignment was understanding the asynchronous flow of thread scheduling and ensuring that context switches were counted accurately. Because multiple threads interact and yield control based on the time quantum, tracking the exact moments when the CPU switches execution context required careful code analysis. Debugging output paths in NetBeans initially presented minor obstacles when running the simulation class. However, carefully tracing the process queue logic helped me overcome these hurdles and achieve the desired simulation behavior.

## Question 3: How did you overcome the challenges you faced?
I overcame these challenges by systematically reading the entire `SchedulerSimulation.java` file from top to bottom and analyzing how the queue handles thread preemption. Whenever I encountered output anomalies, I added descriptive console print statements to trace process states in real time. Re-reading the `README.md` instructions and breaking down the requirements into smaller implementation steps made the debugging process much more manageable. Testing the program after each incremental change ensured that every feature worked correctly before moving forward.

## Question 4: How can you apply multithreading concepts in real-world applications?
Multithreading concepts are essential in modern software development for building responsive, high-performance applications. For instance, in web browsers, separate threads handle network requests, UI rendering, and script execution simultaneously to prevent freezing. In mobile applications, background threads perform heavy data processing or file downloads while keeping the user interface smooth and interactive. Similarly, multi-player video games utilize concurrency to manage physics calculations, AI behaviors, and rendering loops concurrently.

---

# Part C: Technical Answers (0.5 mark)

## Question 1: Thread vs Process
A process represents an independent execution environment with its own isolated memory space, whereas a thread is the smallest unit of execution within a process that shares memory and resources with other threads. In this assignment, we used Java threads (`new Thread(process)` as seen in `addProcessToQueue()`) instead of separate system processes because threads share the heap memory efficiently and have much lower creation overhead. This allows lightweight communication and synchronized state management across our simulated ready queue without the heavy inter-process communication overhead required by actual operating system processes.

## Question 2: Ready Queue Behavior
In Round-Robin scheduling, when a process does not finish executing within its allocated time quantum, it is preempted and placed back at the end of the ready queue. In my program output, process `P1` had a large burst time exceeding the quantum, causing it to yield control and re-enter the queue multiple times (e.g., re-queued after its first 5000ms quantum execution). Re-queueing is crucial for fairness because it prevents long-running processes from monopolizing the CPU, ensuring that every process gets an equal opportunity to execute responsive to its priority.

Example from my output:

P1 executing quantum [5000ms]
P1 completed quantum 5000ms | Overall progress: 49%
P1 yields CPU for context switch
P1 added to ready queue | Burst time: 10099ms | Priority: 6

Explanation of example:
This output snippet demonstrates process P1 finishing its time quantum slice, yielding the CPU due to preemption, and being successfully re-enqueued back into the ready queue to await its next scheduling cycle.

Question 3: Thread Lifecycle
New: P1 enters the New state when an instance of the Process class is instantiated before its associated thread is initialized.

Runnable: P1 becomes Runnable when Thread.start() is invoked within the scheduler loop, transitioning the thread to the system's runnable pool.

Running: P1 enters the Running state when the CPU allocates execution time to its thread, executing the instructions inside the run() method.

Waiting: P1's thread enters a Waiting or timed-waiting state when Thread.sleep() is called to simulate CPU burst consumption and delay intervals.

Terminated: P1 enters the Terminated state after its total burst time is fully exhausted and the run() method finishes execution naturally.

Question 4: Real-World Applications
Example 1 (operating-system level): Operating System CPU Scheduler
Description:
An operating system kernel manages multiple active user applications and system services sharing a single multi-core processor.

Why Round-Robin works well here:
Round-Robin scheduling ensures absolute fairness and responsiveness, guaranteeing that no single runaway application can freeze the entire system by hogging CPU cycles.

Example 2: Web Server Request Handler
Description:
A multi-threaded web server handles thousands of incoming client HTTP requests concurrently using thread pools and task queues.

Why Round-Robin works well here:
It ensures predictable response times and equitable CPU distribution among concurrent client connections, preventing starvation under heavy web traffic.

✅ Final Checklist (complete before submitting)
Repository

[x] Repository is PUBLIC

[x] Repository is renamed to OS-Assignment1-Reem-Alyahya

[x] GitHub account uses the university email

Code

[x] Student ID is set in SchedulerSimulation.java (line 150)

[x] Code compiles and runs with no errors

[x] Feature 1, Feature 2, and Feature 3 all work

Commits

[x] At least 3 meaningful commits, ideally 6 or more

[x] One commit per feature

[x] Commits are spread over different dates

[x] Everything is pushed to GitHub

This file (MY_WORK.md)

[x] Full name and student ID filled in at the top

[x] Development log has 5+ entries on different dates

[x] Reflection: 4 questions completed

[x] Technical answers: 4 questions completed with examples

[x] No placeholders left

Video

[x] 2-3 minutes long, uploaded and link is public

Blackboard

[x] Submit only the link to your public GitHub repository
