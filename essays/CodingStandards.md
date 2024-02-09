---
layout: essay
type: essay
title: "Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-2-07
published: true
labels:
  - Software Engineering
  - Computer Programming
---

Coding standards are important for a multitude of reasons. The most apparent benefit of using coding standards is in the name itself. Simply put, coding standards create a standard. These standards generate consistency and are extremely helpful when keeping, maintaining, and debugging code. Additionally, they make collaboration much easier and more efficient. 

Let us take a team of programmers that are collectively working on a large and complex program as an example. In the first scenario, each programmer uses their own coding standard or worse yet does not use a consistent standard at all. In this case, the program will be absolute chaos. While the code might technically run, any minor bug will be a major inconvenience. Each programmer will have to expend time and effort simply understanding what their fellow programmers wrote. Instead of focusing on fixing the problem, which is what they should be doing, they must first understand the numerous different styles or lack thereof implemented by fellow developers. Now imagine that instead of this chaos, all programmers utilize one consistent style. In this scenario, bugs can be addressed much more effectively and directly than before. Each programmer will understand the convention and style used by fellow developers because a consistent standard is maintained.

Not only do coding standards create consistency, they also greatly increase code readability. Code readability is very important for writing maintainable programs, especially if more than one programmer must simultaneously work on the same project. Code readability also helps the original author. Overall, having a coding standard will increase the readability of the code. One example that demonstrates this concept can be found in the legal world. Imagine that a lawyer has been hired by a client and must submit a complex legal document to the court. The lawyer writes up the document and then attempts to submit it. While the document is grammatically correct, it has no consistency in formatting. Each header has a different font size, different colors are used randomly, and different fonts are utilized. This document might technically be grammatically correct but it is effectively unintelligible. The court will reject the document until it is submitted in the proper convention. This example parallels how coding standards affect readability. In the same way that the lawyer’s document was grammatically correct but was unintelligible, code without a standard could run but still be unreadable.


Coding Standard Tools

When maintaining coding standards for programs, manually checking to ensure compliance with the standards is neither efficient nor effective. Instead, some form of tool should be used to check that the code is following the standards. Many such tools are available and could even be used to fix issues of noncompliance quickly. One such tool available for Javascript is ESLint. I have used ESLint before and it will generate errors in the program when the code is not in compliance with the coding standards it has been given. At first, it was a bit tedious making sure that every line of code was following the standards but after a while I realized how useful the tool is. ESLint guarantees conformity to the coding guidelines and makes it much simpler to have the readable and easily maintainable code that comes with enforcing coding standards.



