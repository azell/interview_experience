# Interviewing During A Pandemic

## Useful Resources

* [Kevin Naughton Jr. videos](https://www.youtube.com/c/KevinNaughtonJr/videos)
* [Nick White videos](https://www.youtube.com/c/NickWhite/videos)
* [TechLead videos](https://www.youtube.com/c/TechLead/videos)
* [Cracking the top 40 Facebook coding interview questions](https://www.educative.io/blog/cracking-top-facebook-coding-interview-questions)
* [LeetCode](https://leetcode.com/)
* [Preparing for Your Software Engineering Interview at Facebook](https://www.facebook.com/careers/life/preparing-for-your-software-engineering-interview-at-facebook/)
* [GeeksforGeeks](https://www.geeksforgeeks.org/)
* [Program Creek Interview Category](https://www.programcreek.com/category/interview/)
* [Techie Delight](https://www.techiedelight.com/)
* [50 Coding Interview Questions](https://github.com/azell/interview_experience/raw/main/50-Coding-Interview-Questions-V2.pdf)
* [Popular Interview Questions This Year](https://leetcode.com/discuss/interview-question/910825/google-bloomberg-others-interview-questions-this-year)
* [Sample Coding Questions To Review](https://leetcode.com/list/5ahe6ppr/)

## Data Structures To Know

* Arrays
* Graphs
* Hash tables
* Heaps
* Lists
* Queues
* Stacks
* Trees
* Tries

## Algorithms To Know

* Big O notation
  * In space
  * In time
* Binary search
  * [Variants](https://docs.python.org/3/library/bisect.html)
* Breadth first seach
* Depth first search
* Kadane's algorithm
* Merge sort
  * Merging N sorted lists into one sorted list
* Quicksort
* Recursion
  * Memoization
  * Backtracking
* Select Kth element
  * Quickselect
  * Using a heap
* Sliding windows

I did not encounter any dynamic programming questions, though they seem to be popular at Google.

## The Virtual On-Site Interview

The next step after passing a phone screen is the virtual on-site. This typically requires 3 - 6 hours broken up into 45 - 60 minute segments. For senior candidates the segments will cover:

* Coding and problem solving
* Behavioral probing
* System design

### Coding Segments

As the name indicates, this involves solving a problem using code. Instead of a physical whiteboard, you would use something like [CoderPad](https://coderpad.io/). The choice of the programming language is up to you. If possible, I would recommend using Python due to its large standard library and terseness of code. However, it is more important in my opinion to use whatever language you use the most as looking up APIs and syntax can disrupt your coding flow. I used Java for all of my coding segments.

Whenever I was given a problem to solve, I always repeated it back to the interviewer. This is useful to verify that you are solving the right problem, and eliminate any ambiguities in the specification. I would sketch out a couple of possible solutions at a high level and discuss the tradeoffs of each. Once you have identified your best solution, it is a good idea to ask your interviewer if your proposed solution makes sense.

When implementing your solution, it is advisable to break the functionality into small methods and describe the logic while typing. Small methods make testing simpler and provide placeholders when sketching out the overall implementation. Keeping the communication flowing highlights your communication skills, and gives the interviewer a chance to provide hints or course correct.

Here are some of the questions I encountered in real interviews:

* Calculate the maximum path sum of a tree
* Serialize and deserialize a tree
* Given a sorted integer array with duplicate elements, calculate how often a given integer occurs in the array
* Given a dictionary of lowercase words, implement wildcard search where . matches any one character
* Given a string of nested pairs ([], (), {}) determine if the string is well-formed
* Given a list of songs, create an interator that provides random songs without duplicates
* Given an array, create an interator that omits duplicate consecutive elements
* Given a date, return what day of the week the date falls on

### Behavioral Segments

I found this segment the most unpredictable in terms of questions and scope. I would recommend going over your resume, and highlighting both good and bad interactions with your team, manager and peers. You want to provide context and details without rambling. The [STAR technique](https://www.indeed.com/career-advice/interviewing/how-to-use-the-star-interview-response-technique) is popular.

Sample questions:

* Everyone starts somewhere. Talk about a time when you were new on the job and had a lot to learn. How did you manage that?
* Give me an example of a time you faced a conflict while working on a team. How did you handle that?
* How do you like to give and receive feedback?
* Let’s say you’re working on a major project and you’re in the weeds. How do you find your way out?
* Tell me about a situation where you had to solve a difficult problem
* Tell me about a team project you worked on
* Tell me about a time when you advocated for and pushed your own ideas forward despite opposition?
* Tell me about a time when you came up with a new approach to a problem.
* Tell me about a time when you took the lead on a difficult project
* Tell me about a time when you were not able to meet a time commitment. What prevented you from meeting it? What was the outcome and what did you learn from it?
* Tell me about a time when you worked with a difficult team member.
* Tell me about a time you recovered from a difficult situation
* We all deal with difficult customers from time to time. Tell me about a challenging client-facing situation and how you handled it.
* What are you proud of?
* What could you have done better?
* What kinds of technologies are you most excited about?
* What were some excellent collaborations you've had?
* What were some of the best things you've built?
* What's your greatest strength? And weakness?

### System Design Segments

These questions are the least tricky, but require familiarity at multiple levels of the stack (load balancers, pub/sub, security, performance, etc.). I always emphasize monitoring and observability for any system.

Sample questions:

* Design gmail
* Design a service that ingests songs that a user plays, and an API that returns the user's song leaderboard
* Design a service that ingests user metrics, and fires off alerts with minimal latency
* Design a service that returns popular destinations near the user

## What Should You Know

I encountered a lot of tree problems in interviews, so I would emphasize feeling comfortable with recursion, DFS and BFS. A lot of questions that involve backtracking (find the longest palindrome, etc.) can also be solved with recursion. If your solution's run-time is exponential, adding memoization tends to drop the run-time down to quadratic. Tree iterators over pre-order, in-order and post-order traversal are also popular.

A small number of questions can be solved in-place (reversing a string, Dutch national flag problem, etc.). Practice writing loops with multiple indexes over an array as this will also carry over to sliding windows questions.
