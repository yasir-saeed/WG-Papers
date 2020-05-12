# Goals of the Laser Language Embedded Working Group

## General Goals

Papers which complete or advance any of these goals should target the Embedded Working Group.

`[ ]` Improve language and library features so that they are usable in Space or time constrained environements. 
* Exception Unwinding 
* Allocating Types, where available
* Crypto API, where available
* Polymorphic/Dynamic Dispatch

`[ ]` Provide methods of compiling and linking to embedded/freestanding environments, including for os dev
* Split Standard library into various parts which may be provided where the requisite features are available (core, alloc, crypto, std for example) (with Library Design Working Group)
* Provide a method of disabling part of the standard library, and enabling the parts which can be provided

`[ ]` Make Porting the laser language to a new environment, freestanding or hosted, a trivial matter
* Reduce architecture specific code and types written in the standard library
* Provide easy methods to select (and add selections for) architecture specific code and types where necessary
* Reduce or eliminate architecture specific code in the laser language compiler, including the bootstrap compiler
* Work with the Compiler Working Group to maintain the Bootstrap Compiler so it may be used in the process of porting to a new archtecture or os.

`[ ]` Improve Interaction with the Embedded Domain Experts in Other languages

## Collaberative Goals

Papers which complete or advance any of these goals should target the Embedded Working Group, as well as the other Working Groups mentioned for these goals. 
Work on these should closely involve the working groups listed. 

`[ ]` With Game Development and Library Design: improve optimizability of the standard library and reduce space and time complexity of operations in the Standard Library to minimal amounts

`[ ]` With Compiler, make it possible for any architecture supported by LLVM to be a target for the laser language

`[ ]` With Compiler, provide a method to define new targets which may not necessarily be supported by llvm. 

`[ ]` With Game Development and Lang Design, provide language features which can enable optimizations without compremising usability. The Compiler Working Group may also comment on papers for this goal

## Other Goals

Papers which complete or advance any of these goals should not necessarily target Embedded Working Group, but might be commented on by Embedded Working Group

`[ ]` Allow Buildscripts/Package Manifests to specify linker scripts to use


