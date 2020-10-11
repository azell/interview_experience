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

I did not encounter any dynamic programming questions, though they seem to be popular at Google.

## Interview Questions

Here are some of the questions I encountered in real interviews:

* Calculate the maximum path sum of a tree
* Serialize and deserialize a tree
* Given a sorted integer array with duplicate elements, calculate how often a given integer occurs in the array
* Given a dictionary of lowercase words, implement wildcard search where . matches any one character
* Given a string of nested pairs ([], (), {}) determine if the string is well-formed
* Given a list of songs, create an interator that provides random songs without duplicates
* Given an array, create an interator that omits duplicate consecutive elements
* Given a date, return what day of the week the date falls on

## The Virtual On-Site Interview

The next step after passing a phone screen is the virtual on-site.  This typically requires 3 - 6 hours broken up into 45 - 60 minute segments.  For senior candidates the segments will cover:

* Coding and problem solving
* Behavioral probing
* System design

### Coding Segments

As the name indicates, this involves solving a problem using code.  Instead of a physical whiteboard, you would use something like [CoderPad](https://coderpad.io/).  The choice of the programming language is up to you.  If possible, I would recommend using Python due to its large standard library and terseness of code.  However, it is more important in my opinion to use whatever language you use the most as looking up APIs and syntax can disrupt your coding flow.  I used Java for all of my coding segments.

Whenever I was given a problem to solve, I always repeated it back to the interviewer.  This is useful to verify that you are solving the right problem, and eliminate any ambiguities in the specification.  I would sketch out a couple of possible solutions at a high level and discuss the tradeoffs of each.  Once you have identified your best solution, it is a good idea to ask your interviewer if your porposed solution makes sense.

When implementing your solution, it is advisable to break the functionality into small methods and describe the logic while typing.  Small methods make testing simpler and provide placeholders when sketching out the overall implementation.  Keeping the communication flowing highlights your communication skills, and gives the interview a chance to provide hints or course correct.
