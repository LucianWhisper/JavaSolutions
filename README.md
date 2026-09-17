# Java Tutorials
A collection of clean Java starting points for **live tutorials** and **stream collaborations**.

This repository is intentionally kept simple: every tutorial starts from a fresh Java project.

# How It Works
The `main` branch always represents a **brand-new Java project**.

When starting a new tutorial, a new branch is created from `main`, for example:
```
main
│
├── tutorial/variables
├── tutorial/classes
├── tutorial/inheritance
└── tutorial/collections
```

The tutorial branch becomes the **starting point** for that tutorial.
<br>No tutorial code is developed directly on `main`.

## Main
`main` is always kept clean and ready for the next tutorial.

It contains only the basic project setup required to start writing Java code.

When a new tutorial begins, the current `main` branch is used as the base for a new tutorial branch.

## Tutorial Branches
Each tutorial gets its own branch.

For example:
```
tutorial/variables
tutorial/oop
tutorial/interfaces
...
```

These branches establish the starting point and any setup that is specific to that tutorial.

## Following Along
During a tutorial, you'll write the code yourself in your own project.

This repository provides the **starting project**, while the completed code developed throughout the tutorial is maintained separately.

This means you can:
1. Start from the appropriate tutorial branch.
2. Follow along with the stream.
3. Write the code yourself.
4. Experiment and make mistakes.
5. Compare your results with the completed solution afterward.

## Solutions
Completed tutorial code is maintained in a separate repository.

The separation is intentional:
> This repository gives you the starting point.
> <br>The solutions repository contains the code built during the tutorial.

This allows the starting project to remain clean while keeping completed examples available for reference.

## Stream Tutorials
These projects are created primarily for **live Java tutorials** and **stream collaborations**.

The goal isn't just to provide finished code, but to provide a clean environment where we can build, experiment, and learn together.

You can find me live on [Twitch](https://twitch.tv/lucianwhisper)!
<br>And you can find any past tutorials on my [YouTube](https://www.youtube.com/@LucianWhisperVT/streams)!

## Happy Coding!
Start with a blank project.
<br>Write some code.
<br>Break something.
<br>Figure out why it broke.
<br>And learn along the way!