# 64bitAPIHooking

This is an implementation of a hooking engine for 64 bit processes in a Windows environment.

It works by monitoring the creation of a process by using the WMI interface. After a process specified in the command line is created, it will then inject the hooking engine, a DLL, into the process.

The purpose of the DLL is to apply an inline patch in a function specified by the programmer.
