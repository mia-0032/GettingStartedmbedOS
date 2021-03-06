# Introduction to the mbed OS User Guide

This is the mbed OS User Guide. We're publishing it one chapter at a time. 

Currently available: 

* [mbed OS applications with yotta](app_on_yotta.md): The relationship between yotta and mbed OS, and how you can create yotta-based mbed OS applications. 

* [Writing applications for mbed OS](app_on_mbed_os.md): Some general principles of mbed OS applications.

* [Debugging mbed OS applications](Debugging.md): Debugging for applications built with ARMCC and GCC.

* [Security with mbed TLS](mbed_tls.md): Using mbed TLS for communication security in mbed OS.

* [Memory in mbed OS](memory.md): Memory management and allocation in mbed OS. 

* [Networking with mbed OS](networking.md): Networking options and structure on mbed OS.

## Prerequisites

This guide assumes that you are familiar with C++. While we do discuss how we applied some concepts in mbed OS, we don't explain the background to these concepts in any great detail. If you know C but not C++, you might find this [Coursera module](https://www.coursera.org/course/cplusplus4c) helpful.

The examples in this guide focus on the FRDM-K64F board. If you have another board, you'll have to check if it's already [supported on mbed OS](https://www.mbed.com/en/development/hardware/boards/) before you run the sample code. You should be able to follow the code and explanations even if you don't have compatible hardware.
