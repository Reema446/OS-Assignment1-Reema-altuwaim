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
| **Full Name** | [Reema Altuwaim] |
| **Student ID** | [446051373] |
| **University Email** | [446051373@std.psau.edu.sa |
| **GitHub Username** | [Reema446] |
| **Repository Link** | [[(https://github.com/Reema446/OS-Assignment1-Reema-altuwaim.git)] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - [8 october ,2026 ,10:00 pm ]
**What I did**:Created GitHub account and set and update my student id in code

**Details**: i created my gitHub account using my university email, forked the starter repository and renamed it and updated my student ID inside SchedulerSimulation.java at line 150

**Challenges**:is ensuring the repository settings were correctly configured as public because i dont know anything about github

**Solution**:verified repository visibility and account email synchronization

**Time spent**:2 hours

---

### Entry 2 - [9 october ,2026,5:00pm]
**What I did**: installed VS Code and set up the development environment

**Details**:i downloaded and installed Visual Studio Code configured  JDK extensions, and set up the local workspace to prepare for project implementation

**Challenges**:configuring the environment paths for the Java compiler

**Solution**:verified jdk installation and integrated it properly with VS code extensions

**Time spent**:1 hour

---

### Entry 3 - [10 october ,2026,9am]
**What I did**:analyzed assignment requirements 

**Details**:i read the assignment file and try to understand all requirements and parts

**Challenges**:understanding the concepts of round roibn RR

**Solution**: review RR

**Time spent**:1 hour

---

### Entry 4 - [11 october ,2026, 7:00 am]
**What I did**: implemented all 3 features

**Details**: i developed feature 1 (process priority generation) feature 2 (context switch counter)and feature 3 (waiting and turnaround time calculations using System.currentTimeMillis()

**Challenges**:keeping track of total waiting times correctly when processes got suspended and interrupted and re-queued multiple times in the ready queue

**Solution**:added precise state tracking variables and timestamps to cleanly accumulate active waiting durations across multiple round-robin cycles

**Time spent**: 6 hours

---

### Entry 5 - [11 october , 2026, 4pm]
**What I did**:completed documentation and project organization

**Details**: organized the final code structure and completed all documentation requirements

**Challenges**:verifying commit history

**Solution**:double-checked all markdown elements

**Time spent**: 2hours

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

**Total time spent on assignment**: [11 hours]

**Most challenging part**:i think the hardest part was calculating waiting and turnaround times accurately because processes were repeatedly paused and re-queued during Round-Robin scheduling

**Most interesting learning**:seeing multithreading run in real-time helped me understand how the OS scheduler controls threads and switches execution

**What I would do differently next time**: ofc i will set up the environment and review instructions earlier to avoid feeling rushed during video recording

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

[working on this assignment actually made me understand how java handles multithreading much better, i learned how to create threads and use thread.start to get them running concurrently without issues, using thread.join was coool because it helped me wait for threads to finish up before moving on, i also used thread.sleep to mimic actual work time and see how the scheduler pauses stuff, honestly seeing the program switch back and forth between different threads in real time was pretty surprising and cool, it just made everything click about how os manages processes]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[most challenging part for me was definitely reading through the starter code and understanding how the scheduler logic was built, it took me a while to trace how the threads andd processes and the ready queue were actually interacting with each other, at first glance the execution loop looked super confusing and i was not sure where to insert my new features without breaking the existing flow,i had to read the code line by line and print out some debugging statements just to see what was happening behind the scenes, once I clearly understood how the execution loop worked adding my features became a lot easier.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[i handled the challenges by keeping my workflow simple and testing my changes as i went along, i added a few print statements in vs code to check the thread values and make sure the queue was updating right, checking the readme instructions again helped me verify that my logic matched what the assignment asked for, i made small adjustments one at a time and ran the simulation after each change to verify it worked, when something did not match the expected output i just traced the variables in my code to locate the issue, taking a organized approach made it pretty easy to fix bugs and finish the features]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[multithreading is very very important in real world apps to stop them from freezing, for instance web browsers use threads to load images and run scripts at the same time, video games use separate threads for playing audio while rendering graphics smoothly, music apps also run background threads so music keeps playing while you scroll, working on this scheduler showed me how operating systems keep apps responsive]

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

[in our code a process is simulated as a java class while each one runs inside a real java thread created using new thread process,a process has its own isolated memory space and higher creation overhead whereas threads share the same memory space and switch much faster, we used threads in this assignment because creating heavy system processes for all sixteen simulated tasks would be inefficient and slow, by using threads inside schedulersimulation.java we could easily manage the ready queue and handle context switching smoothly]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[when a process does not finish within its time quantum during round robin scheduling the cpu pauses its execution and performs a context switch,  in my output process p3 had a burst time of 10625ms and time quantum of 5000ms causing it to be re-queued two times before completings,re-queuing ensures fairness by preventing long processes from monopolizing the cpu and giving every process an equal opportunity to execute]

Example from my output:
```
[? P3 executing quantum [5000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P3 completed quantum 5000ms │ Overall progress: [█████████░░░░░░░░░░░] 47%
     Remaining time: 5625ms
  ? P3 yields CPU for context switch

  ? P3 (Priority: 4) added to ready queue │ Burst time: 10625ms]
```

**Explanation of example:**
[this code show process p3 running for its full quantum of 5000ms but failing to finish because its remaining burst time is still 5625ms, because it ran out of time it yields the cpu and gets pushed back to the ready queue to wait for its next turn]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [created when the thread object is instantiated using new thread process]

2. **Runnable**: [starts right after thread.start is called in the scheduler loop]

3. **Running**: [begins when the thread executes code inside its run method]

4. **Waiting**: [happens when calling thread.sleep or waiting on join]

5. **Terminated**: [reached once the run method finishes execution]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [os cpu task scheduling]

**Description**:
[ operating system shares cpu time among active user programs like visual studio code and background services , each program acts like a process and receiving a small time slice to run on the processor, if a program does not finish during its allocated time a context switch occurs to let the next process run]

**Why Round-Robin works well here**:
[round robin ensures strict fairness so no single background application can freeze the system , giving every process an equal time quantum maintains system responsiveness and keeps all open programs running smoothly]

### Example 2: [web server handling user requests]

**Description**:
[a web server handles hundreds of incoming HTTP requests at the same time using background threads , each thread processes one request where time quantum is the cpu time allocated per request before switching , context switching allows the server to serve multiple users without making anyone wait too long]

**Why Round-Robin works well here**:
[round robin provides great responsiveness and predictability for all connected users , it prevents a large file download request from blocking smaller web page requests and ensuring fair service for everyone]

## Summary

**Key concepts I understood through these questions:**
1.how round robin works with time quantums
2.difference between threads and processes
3.thread lifecycle states

**Concepts I need to study more:**
1.thread synchronization in java
2.calculating waiting time for queues

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
