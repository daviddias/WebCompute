![](/graphs/webcomputer-logo.png)

> Research for Parallel Computing on top of the Web Platform

# Intro

Following up on the the research I've performed for my MSc, [browserCloud.js](https://github.com/diasdavid/thesis.browserCloud.js/blob/master/document.pdf), I've decided to continue working towards the goal of taking advantage of the Browser, the most Ubiquitous platform, to create a parallel runtime to leverage idle resources in user machines. These users would opt to volunteer (a la SETI@HOME, FOLDING@HOME, etc project) or incentivised (a la bitcoin, filecoin, etc).

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

# Research and development endeavours

- [webrtc-explorer](https://github.com/diasdavid/webrtc-explorer)

# Articles and updates

- [webrtc-explorer - Resource Discovery for decentralized browser networks](http://blog.daviddias.me/2015/03/22/enter-webrtc-explorer)
- [Resource discovery through WebRTC - webrtc-ring](http://blog.daviddias.me/2014/12/20/webrtc-ring)

# Everyone is welcome to participate :)

You are welcome to open issues with questions, ideas, contribute to the list of endeavours, create a project towards the same goal and discuss potential new ways to make it more interesting! :D
