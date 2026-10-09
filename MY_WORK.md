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
| **Full Name** | [Saad Abdulaziz Hilayel] |
| **Student ID** | [446050203] |
| **University Email** | [446050203@std.psau.edu.sa |
| **GitHub Username** | [saad-abdulaziz-2222 |
| **Repository Link** | [https://github.com/saad-abdulaziz-2222/OS-Assignment1-Saad-Hilayel] |
 
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
### Note on GitHub commit timestamps

In this assignment I noticed that some of my commits were shown as being made at the same time or grouped under the same date on GitHub even when I worked on the features separately. I used Visual Studio Code to control my commit to Git and sync my local repo to GitHub . I also had a sync problem where I needed to pull . I don’t know if it’s something in my git workflow that caused the timestamps to appear, so I don’t want to assume it’s that without verifying. The GitHub history shows the commits as displayed by the platform, whereas my development log aims to describe the work I actually did.

### Entry 1 - October 6, 2026, [Around 8:40 p.m.

What I did: 1. Created my assignment repo and started working on the java project.

Details:

I forked the starter repository provided and used the repository name required, which is OS-Assignment1-Saad-Hilayel.
- reviewed repository files and assignment instructions
The studentID setting in SchedulerSimulation.java.

Challenges: I had to understand the starter project and what parts needed to be changed for the assignment.

Solution: I reviewed the project structure and followed the assignment instructions to locate the changes needed.

Time spent: around 50 minutes]
---

### Entry 2 - October 7, 2026 [11am]

What I did Feature 1: Process Priority

Details:

Added priority field to the simulated Process class.
Set a random priority between 1 and 10 with 10 being the highest priority.
Added a getter for priority.
Show the priority when a process enters the ready queue.
Maintained original FIFO queue order.
Feature 1: Monitor process priority in ready queue. Feature committed with message

Challenges: I needed to inject priority information without disrupting the original scheduling order.

Solution: I added the priority as extra information, and left the FIFO queue implementation as it was.

Time spent: [1 to 1:30 hours.]
---

### October 7, 2026, [3:40]

What I did is implement Feature 2: Context Switch Counter.

Details:

Define a static counter in the SchedulerSimulation class.
Each time the scheduler started a process thread , the counter was incremented .
Added an output statement to print the total counter at the end of the simulation
Added the feature with the commit message: "Feature 2: Add context switch tracking".

Challenges: I had to put the counter increment in the scheduler loop, and ensure that it was declared in the correct scope.

Solution: I declared counter outside main() and incremented it in the scheduling loop before currentThread.start()

Time spent: [2-3 hours.]
---
### Entry 4 October 8, 2026 [4:25PM]

**What I Did:** I implemented Feature 3 on SchedulerSimulation.java and synced my local repo with github.

Details:

* Developed and implemented Feature 3.
* Synced my repository to GitHub using Visual Studio Code.
Saw a prompt to pull changes and saw `SchedulerSimulation.java` in Merge Changes.
- Reviewed the merge conflict to see how I can keep my implementation

**Problems:** I had to resolve a merge conflict in the synchronization process by reconciling my changes with the one in GitHub.

**Solution:** Verified conflict prior to accepting either side to prevent overwriting my implementation of Feature 3.

**Time spent :** 30-45 minutes

---

### Entry 5 - October 8, 2026. [5:17PM]

What I did: Fixed my student ID. Worked on feature #3: Waiting Time Tracking.

Details:

Corrected student id in SchedulerSimulation.java from the wrong original to 446050203.
Committed the fix with message Set my student ID: [446050203]
Contributed to the waiting-time feature, which tracks waiting time and displays turnaround time.

Challenges: The student ID was wrong initially, so I had to do a separate correction. Also, I had to implement the waiting-time feature without unnecessary modifications to the original scheduler.

Solution: I did the student id correction as a separate commit, and the waiting-time feature as a separate change.

time spent : [5 minutes]

---


Entry 6 – Oct 9, 2026, [3:30]

What I did: Reviewed the assignment documentation requirements. Prepared my dev log.

Details:

Reviewed required sections in MY_WORK.md.
I looked at the history of my repo vs. the work I had done.
Started documenting the features, student id fix, and git sync problem.
Reviewed technical and required reflection questions.

Challenges: I had to make sure that the log reflected the actual work sessions and that my answers would be backed up by my actual code and program output.

I sorted the work by date and feature and identified what details still needed to be verified before submission.

Time Taken: [4 hours]
---

## Development Log Summary

> **Total hours on assignment**: [10 hours 10 minutes~]

Most difficult part: Implementing Feature 3 and dealing with the git sync conflict without losing my changes.

**Most interesting learning:** Learning to implement new functionality in Java and how Git synchronization and merge conflicts work in Visual Studio Code.

**What I would do differently next time**: I would sync my local repo to github more often and check for remote changes before adding new features to reduce the chance of merge conflicts.

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

Multithreading allows the Java program to perform tasks through different threads. In our case, Process implements the Runnable interface, and Thread process is a new thread that is able to execute the run() method of Process. The method Thread.start() starts a thread while Thread.sleep() causes it to sleep between the progress updates. The method Thread.join() causes the main thread to wait until the thread of the current process completes its time slice. I discovered that the scheduler maintains the simulated processes and Java threads that execute them separately. It is surprising that the scheduler waits for the completion of each thread's time slice before switching to another one.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

However, Feature 3, which is waiting time calculation, was the most difficult one for me because of the fact that the timer for waiting needs to be measured each time a process is added to the ready queue. For that reason, I used markReady() to note down the time for this and also used recordWaitingTime() in order to add the time when a process was waiting before execution. Another task for me was ensuring that a process would be able to be added back to the queue without losing its waiting time that was accumulated. In order to do that, I reviewed the last table after simulating the program.
## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I began by reading the README and looking at the Java code to see how the scheduler worked. Then I worked on the three features and ran the program to see if my changes worked. For Feature 3, I used markReady() and recordWaitingTime() to record the time each process spent waiting in the ready queue. I have checked the final summary to see the turn around time and waiting time of each process. When I hit the Git sync issue, I stopped and looked at the merge conflict rather than just accepting one version or the other. This prevented me from overwriting my changes by accident.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

When I write an application that needs to do more than one thing at a time, I can put my knowledge of multithreading to use. For example, a music player can play songs while the user looks at a playlist. A web browser can download content from a website, and still be responsive to user actions. Games can also perform background jobs, while keeping the gameplay responsive. My scheduler helped me understand how processes can be queued, and given time to run. I also learnt how Thread.sleep() and Thread.join() works with execution of a thread. These concepts will help me in understanding how to deal with tasks in future Java projects.

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

In this program, Process is an object that represents a process and is not necessarily an operating system process. In addProcessToQueue(), new Thread(process) creates a thread for the Process object which runs the run() function for the Process object. Threads in the same Java application have access to the memory of the program, whereas different operating system processes usually have their own address spaces. It was better to use threads as opposed to creating multiple processes since threads were much easier to make and communicate with, but could still simulate each process object using Runnable.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

If the process does not complete its time quantum, it is placed at the end of the ready queue, if there are other processes waiting. In my output P5 has burst time 8420 ms and time quantum 4000 ms. It runs for 4000 and then it gets re-queued, it runs for another 4000 ms, it gets re-queued again and finally it runs for its remaining 420 ms. P5 was thus re-queued twice before it was finished. This helps to keep the scheduling fair as the other processes get their turns instead of one process hogging the CPU until it completes.

Example from my output:
```
P5 executing quantum [4000ms]
P5 completed quantum 4000ms
Remaining time: 4420ms
P5 yields CPU for context switch

P5 added to ready queue | Burst time: 8420ms

...

P5 executing quantum [4000ms]
P5 completed quantum 4000ms
Remaining time: 420ms
P5 yields CPU for context switch

P5 added to ready queue | Burst time: 8420ms

...

P5 executing quantum [420ms]
P5 finished execution!
```

**Explanation of example:**
The burst time of P5 is 8420ms but the time quantum is only 4000ms. It executes for 4000 ms in its first turn, leaving 4420 ms, and it is put back into the ready queue. On its second turn it runs for another 4000 ms, leaving 420 ms so it gets rescheduled again. Finally P5 runs for the remaining 420ms and finishes. This is to demonstrate what Round-Robin does, in that it allows other processes to take their turn instead of letting P5 have the CPU until it finishes.
## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New:** When `addProcessToQueue()` creates a P1 thread using `new Thread(process)`, it is in the New state.

2. **Runnable:** P1 will be in the Runnable state when `currentThread.start()` is called by the scheduler.

3. **Running:** P1 runs its `run()` method, performing CPU work and decrementing its remaining time.

4. **Waiting:** The call to `Thread.sleep(stepTime)` puts P1’s thread in the timed-waiting state. The main thread calls `currentThread.join()` to wait for P1 to complete.

5. **Terminated**: P1’s thread terminates when its `run()` method has completed its time slice. If P1 still has time remaining, the scheduler will create a new thread for the next round of P1.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

Example 1 (Operating system level): CPU time sharing A very simple operating system can make use of Round-Robin method for distributing CPU time between runnable processes or threads. In this example, each runnable process plays the role of the process in my simulation, and the time quantum is set by the scheduler to indicate the time period during which one process would be allowed to execute before being replaced by another one. If there is an unfinished process, it can come back to the end of the ready queue in order to allow other processes to run. Changing from one process to another one is called a context switch. 
Example 2: Multiplayer game server The server of the multiplayer game needs to deal with independent jobs, such as performing actions requested by players, game world updating, background data saving, etc. The server can put all such jobs in the ready queue and allocate a certain time slice for each job, like in my simulation. In case there is an unfinished job, it can go back into the queue while the server deals with other jobs. Context switching happens when the operating system moves the CPU from one working thread to another..



## Summary
Key concepts I understood through these questions: 
I found out that Round-Robin scheduling allocates a little bit of CPU time to each process and any processes not finished are placed back into the ready queue. I had a vague idea how java threads work with methods such as start(), sleep(), join() and how state of a thread changes during execution. From context switches and waiting time I learned how to judge the effectiveness of a scheduling algorithm in dealing with processes. 
Concepts I need to study more:
I need to get a better understanding of how real operating systems do context switches and schedule threads. I want to practice calculating the waiting time and how different values of time quantum will impact the scheduling performance



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
