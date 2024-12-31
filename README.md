# Objective-C ARC Retain Cycles and Delegate Memory Management

This repository demonstrates common memory management issues in Objective-C using Automatic Reference Counting (ARC).  Specifically, it highlights retain cycles and improper delegate handling, both leading to memory leaks and potential crashes.

## Bug Description
The `bug.m` file contains code that exhibits a retain cycle and improper delegate management. This results in objects not being released, leading to increased memory usage and potential application instability.

## Solution
The `bugSolution.m` file presents corrected code that avoids the retain cycle and manages delegates appropriately.  It showcases best practices for memory management in Objective-C with ARC.

## How to Run
1. Clone the repository.
2. Open the project in Xcode.
3. Build and run the application.
4. Observe the memory usage and application behavior with both the buggy and the corrected versions.