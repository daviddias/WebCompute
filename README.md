browserCloudjs
==============

![](/logo/logo-small.png)

> Parallel Computing Research on top of the Web Platform

# Project Description

browserCloudjs was the title I selected for my MSc thesis in P2P Networks, the main goal was to infer if Web Technologies could offer a parallel runtime for running jobs, leveraging idle resources through volunteer cycle sharing, taking into account bandwidth necessary and still offering speedups when compared to other Single or Parallel Runtimes. Results can be found in the end of the document.

My intent is to continue working on this subject, improving the characteristics of the system and finding new ways to enhance the quality of the results.

# Technical challenges

In order to build and optimize a parallel computing platform using Web technologies as the transport to move data around and the engine to compute that data, we have to test and experiment different approaches to solve the following technical challenges:

- Communication between entities 
  - centralised vs decentralised vs distributed.
  - recursive (store and forward, e.g: IP) or iterative
  - message queues
- Performing computation
  - WebGL vs WebAssembly vs normal JS runtime
- JS sandboxing
- Shipping the code to the browsers (code signing, loading, etc)
- And many others

# Current endeavours and outcomes

 - webrtc-explorer
 - simple-raytracer
 - ..

# Everyone is welcome to participate :)

Feel welcome to open issues with questions, ideas, contribute to the list of endeavours, create a project towards the same goal and discuss potential new ways to make it more interesting.
