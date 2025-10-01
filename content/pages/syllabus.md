---
content_type: page
description: This syllabus section provides the course description and information
  on course meeting times, the standard software environment used for the course,
  and how to mimic that environment on your own computer.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus and Software
uid: 01ee04e1-38b0-9ea0-c906-e9d57f619319
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week for 4 weeks, 1 hour / session

Labs: 2 sessions / week for 4 weeks, 1 hour / session

Course Description
------------------

This course provides a fast-paced introduction to the C and C++ programming languages. You will learn the required background knowledge, including memory management, pointers, preprocessor macros, object-oriented programming, and how to find bugs when you inevitably use any of those incorrectly. There will be daily assignments and a small-scale individual project.

Software
--------

### Standard Environment

It's most efficient for the staff if everyone uses the same environment:

*   Athena command-line
*   Compiling: gcc, g++
*   Debugging: gdb, valgrind
*   Editing: nano, pico, vim, or emacs

You can mimic that environment on your own computer:

*   **Windows:** All the necessary packages (except valgrind) are available in {{% resource_link "0b9edefc-be9f-429f-9545-09dd939ff41c" "cygwin" %}} (gcc-core, gcc-g++, gdb).
*   **OS X:** {{% resource_link "e00f5c19-2b94-4fd4-a616-c806f4e88922" "Install Xcode from the App Store" %}}, open it, go to Preferences > Downloads > Components and download "Command Line Tools".
*   **Linux:** `sudo apt-get install build-essential` or equivalent.

### IDEs

If you'd like to use a GUI instead (and there are many good reasons to do so), we'll try to help you out, but:

*   Your programs still need to work in the standard environment, so you should test them there.
*   One of our primary debugging tools (valgrind) may not be available in your IDE.

Nevertheless, these IDEs seem to work well:

*   {{% resource_link "e5120386-1dba-4510-b7de-e27fddd27e5f" "Code::Blocks" %}} (Windows, Linux, OS X)
*   {{% resource_link "08e2af23-6322-4b50-b334-356cd14201aa" "Eclipse" %}} (Windows, Linux, OS X)
*   Visual Studio (Windows)
*   {{% resource_link "e00f5c19-2b94-4fd4-a616-c806f4e88922" "Xcode" %}} (OS X)