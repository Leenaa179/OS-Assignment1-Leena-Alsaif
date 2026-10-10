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

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Leena Alsaif |
| **Student ID** | [445052525] |
| **University Email** | 445052525@std.psau.edu.sa |
| **GitHub Username** | Leenaa179 |
| **Repository Link** | https://github.com/Leenaa179/OS-Assignment1-Leena-Alsaif |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1kWr7h5S8dmaXwOwCPRIDy6jpDFPE8oOs/view?usp=drive_link]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

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

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 4, 2026, 7:00 PM]
**What I did**: Forked the repository, configured Git credentials, and set my Student ID.

**Details**:
- Forked the starter repository on GitHub and renamed it to `OS-Assignment1-Leena-Alsaif`.
- Set my global Git config using `Leenaa179` and my university email `445052525@std.psau.edu.sa`.
- Updated line 129 in `SchedulerSimulation.java` with my Student ID `445052525`.
- Compiled and ran the initial starter code successfully.

**Challenges**: VS Code Language Server failed to resolve the Java project JDK path initially.

**Solution**: Reloaded the VS Code window and manually selected JDK 17 in Java Project Settings.

**Time spent**: 1 hour

---

### Entry 2 - [October 7, 2026, 8:30 PM]
**What I did**: Implemented Features 1, 2, and 3 (Dynamic Priority, Context Switch Tracking, and Performance Audit Table).

**Details**:
- Integrated Feature 1: Added `priorityLevel` field and getter method to `Process` class, generating random scores (1–5) seeded with Student ID `445052525`.
- Integrated Feature 2: Implemented `contextSwitchCount` tracking in `SchedulerSimulation` to record total CPU preemptions and display context switch metrics.
- Integrated Feature 3: Tracked process wait times and turnaround times, and constructed a formatted ASCII Performance Audit Table upon execution completion.

**Challenges**: Context switch counter was overcounting initial process enqueue operations.

**Solution**: Isolated the increment counter strictly to the preemption/re-queueing block inside the scheduling loop.

**Time spent**: 3 hours

---

### Entry 3 - [October 8, 2026, 5:00 PM]
**What I did**: Output formatting, execution testing, and edge-case verification.

**Details**:
- Conducted multiple simulation runs using Student ID `445052525` seed to verify colored ANSI terminal output formatting.
- Tested single-process edge cases to ensure the last process correctly executes to completion (`runToCompletion()`).
- Verified thread execution logs to confirm context switches and waiting times are calculated without race conditions.

**Challenges**: ANSI color codes were not rendering properly on default Windows CMD terminals.

**Solution**: Configured the simulation execution environment in VS Code Integrated Terminal with full UTF-8/ANSI support enabled.

**Time spent**: 1 hour

---

### Entry 4 - [October 9, 2026, 2:00 PM]
**What I did**: Final repository verification and documentation in `MY_WORK.md`.

**Details**:
- Completed all reflection questions, architecture explanations, and feature summaries in `MY_WORK.md`.
- Verified that all commits on GitHub reflect correct authorship `Leenaa179 <445052525@std.psau.edu.sa>`.
- Conducted a final code walkthrough to ensure comments and structure follow university standards.

**Challenges**: Aligning repository documentation structures with submission requirements.

**Solution**: Reviewed assignment rubrics to ensure all mandatory sections are fully answered.

**Time spent**: 1 hour

---

### Entry 5 - [October 9, 2026, 5:30 PM]
**What I did**: Final git push and Blackboard submission.

**Details**:
- Performed final code clean-up, removing unused imports and debug print statements.
- Pushed final updates to GitHub repository `OS-Assignment1-Leena-Alsaif`.
- Submitted repository link and `MY_WORK.md` file to Blackboard.

**Challenges**: Ensuring local workspace state matches the remote GitHub main branch prior to submission.

**Solution**: Executed `git status` and `git push origin main` to confirm no uncommitted changes remained.

**Time spent**: 1.5 hours

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

*Total time spent on assignment*: 8 hours

*Most challenging part*: Managing thread preemption state tracking for accurate waiting time calculation and ensuring proper Git commit history alignment.

*Most interesting learning*: Understanding how CPU time quanta create the illusion of parallel execution and how context switching incurs overhead in OS scheduling.

*What I would do differently next time*: Plan commit author metadata verification ahead of initial setup to streamline submission preparation.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[Through this assignment, I gained practical insight into thread management and synchronization in Java. I learned how Thread.start() creates a new path of execution while Thread.sleep() simulates CPU burst execution without blocking the entire JVM. Utilizing Thread.join() allowed me to synchronize the main thread with worker threads, ensuring execution metrics were captured accurately only after all processes completed. I was surprised by how fast thread preemption happens and how much scheduling logic is required to coordinate concurrent threads smoothly. Overall, it demystified how operating systems handle simultaneous process execution using time slicing.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was isolating and tracking context switches accurately during Round-Robin preemption. Initially, my context switch counter was overcounting because it incremented during the initial process enqueuing phase rather than exclusively during process preemptions. I had to carefully trace the execution flow inside SchedulerSimulation.java to ensure that context switches were recorded only when a process consumed its full time quantum and was re-queued. Debugging this required printing execution state transitions step-by-step. Ensuring that waiting time calculations remained accurate during these preemptions added an extra layer of complexity.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcome these challenges by adopting a systematic debugging approach and analyzing thread behavior step-by-step. I added detailed log output statements using System.out.println to monitor process state changes, burst time decrements, and queue movements in real time. I re-read the starter code in SchedulerSimulation.java multiple times to understand how Runnable objects interact with the scheduling loop. Testing small code modifications incrementally helped verify that edge cases, such as a process finishing exactly on a quantum boundary, were handled gracefully. Additionally, reviewing Java multithreading documentation helped refine my understanding of thread states.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading concepts are essential for building responsive and efficient real-world software systems. For example, in a modern web browser, separate threads are dedicated to rendering the user interface, executing JavaScript, and downloading network assets concurrently. Similarly, backend web servers use thread pools to handle thousands of incoming client requests simultaneously without blocking overall application availability. In mobile application development, intensive database or network tasks are offloaded to background threads to prevent UI freezing. Implementing Round-Robin scheduling in this assignment directly reflects how real OS schedulers slice CPU time to ensure fair resource allocation among active applications.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A *process* is an independent executing program with its own dedicated memory space, whereas a *thread* is an execution path within a process that shares memory and resources with other threads of the same process. In SchedulerSimulation.java, we used threads instead of actual operating system processes because thread creation and context switching have significantly lower overhead and allow shared state tracking. Two specific differences are memory sharing (threads share the heap, whereas processes require explicit Inter-Process Communication) and creation overhead (creating a Java thread via new Thread(process) is much faster than spawning an OS process). In our code, each simulated Process implements Runnable and is executed by a real Java thread initialized in addProcessToQueue().]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, when a process does not complete its execution within its allocated time quantum, the scheduler preempts it, pauses its execution, and appends it back to the end of the ready queue. For example, in my program run with Student ID 445052525, process P2 arrived with a total burst time of 8 units; given a time quantum of 3, P2 was executed for 3 units, preempted, and re-queued *2 times* before it finally completed its remaining burst time. Re-queueing is vital for fairness because it prevents long-running CPU-bound processes from monopolizing the processor, ensuring that every active process gets an equal opportunity to execute within a predictable time window.]

Example from my output:
```
[[SCHEDULER] Executing P2 (Remaining Burst: 8, Priority: 4)
[P2] Executing for quantum 3...
[SCHEDULER] Time quantum expired for P2. Preempting...
[SCHEDULER] P2 re-queued to Ready Queue. Total Context Switches: 3]
```

**Explanation of example:**
[Process P2 arrived with a total burst time greater than the time quantum (8 > 3)[span_0](start_span)[span_0](end_span). After executing for 3 time units, its remaining burst time became 5[span_1](start_span)[span_1](end_span). The scheduler triggered a context switch, incremented the contextSwitchCount to 3, logged the preemption, and re-queued P2 at the back of the ready queue so other waiting processes could receive CPU execution time[span_2](start_span)[span_2](end_span).]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [enters the **New* state when its instance and thread object are instantiated inside addProcessToQueue() via Thread t = new Thread(p1)]

2. **Runnable**: [ P1 transitions to **Runnable* when the scheduler invokes t.start(), placing the thread into the JVM ready pool waiting for CPU execution time.]

3. **Running**: [P1 enters the **Running* state when the scheduler thread selects it from the queue and allocates CPU time to execute its run() method logic.]

4. **Waiting**: [4. P1 enters the **Waiting* / *Timed Waiting* state when it simulates processing time by calling Thread.sleep(quantumDuration) inside run(), or when the main thread calls t.join() waiting for P1 to terminate.]

5. **Terminated**: [5. P1 reaches the **Terminated* state upon fully completing its total burst time and returning from its run() method execution.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Time-Sharing in Desktop Operating Systems]

**Description**:
[Modern operating systems like Linux and Windows use time-sharing schedulers to manage concurrent user applications such as text editors, background music players, and system updaters running on a single physical CPU core]

**Why Round-Robin works well here**:
[Round-Robin guarantees high responsiveness and fairness by allocating small time slices to every active application. This prevents a background computation task from freezing the user interface, giving the user a seamless multitasking experience.]

### Example 2: [Web Server Request Handling]

**Description**:
[An enterprise HTTP web server (such as Apache or Tomcat) receives concurrent incoming API requests from hundreds of users and distributes worker thread processing using Round-Robin scheduling queues.]

**Why Round-Robin works well here**:
[It ensures predictable latency and prevents starvation for lightweight user requests when heavy database queries are executing simultaneously. Every client request receives periodic execution cycles, maintaining reliable service level agreements (SLAs).]

## Summary

**Key concepts I understood through these questions:**
1.  How Round-Robin time slicing prevents process starvation and ensures CPU fairness.
2. The operational difference between Java runnable threads and OS process abstractions.
3. Thread state transitions and how context switching introduces runtime overhead.

**Concepts I need to study more:**
1. Advanced synchronization primitives like Mutexes and Semaphores to handle shared resources.
2. Multi-Level Feedback Queue (MLFQ) dynamic priority adjustment algorithms.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
