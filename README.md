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

# Research and Development

## David Dias MSc in Peer-to-Peer Networks by Technical University of Lisbon

[![](https://img.shields.io/badge/INESC-GSD-brightgreen.svg?style=flat-square)](http://www.gsd.inesc-id.pt/) [![](https://img.shields.io/badge/TÉCNICO-LISBOA-blue.svg?style=flat-square)](http://tecnico.ulisboa.pt/) [![](https://img.shields.io/badge/project-browserCloudjs-blue.svg?style=flat-square)](https://github.com/diasdavid/browserCloudjs)

This work was developed by David Dias with supervision by Luís Veiga, all in INESC-ID Lisboa (Distributed Systems Group), Instituto Superior Técnico, Universidade de Lisboa, with the support of Fundação para a Ciência e Tecnologia. 

More info on the team's work at: 
- http://daviddias.me
- http://www.gsd.inesc-id.pt/~lveiga

If you use this project, please acknowledge it in your work by referencing the following document:

David Dias and Luís Veiga. browserCloud.js A federated community cloud served by a P2P overlay network on top of the web platform. INESC-ID Tec. Rep. 14/2015, Apr. 2015 (under submission)

- Paper
  - pdf https://github.com/diasdavid/paper.browserCloud.js/blob/master/index.pdf
  - git https://github.com/diasdavid/webrtc-explorer-t https://github.com/diasdavid/paper.browserCloud.js
- Thesis
  - pdf https://github.com/diasdavid/thesis.browserCloud.js/blob/master/document.pdf 
  - git https://github.com/diasdavid/thesis.browserCloud.js
- Project proposal
  - pdf https://github.com/diasdavid/project.browserCloud.js/blob/master/index.pdf
  - git https://github.com/diasdavid/project.browserCloud.js
- Code Repos
  - https://github.com/diasdavid/webrtc-explorer
  - https://github.com/diasdavid/webrtc-explorer-signalling-server
  - https://github.com/diasdavid/webrtc-explorer-browser-process
  - https://github.com/diasdavid/piri-piri
  - https://github.com/diasdavid/webrtc-explorer-simulator
  - https://github.com/diasdavid/webrtc-chord
  - https://github.com/diasdavid/webrtc-ring
  - https://github.com/diasdavid/webrtc-explorer-visualizer
  - https://github.com/diasdavid/raytracer-browser-p2p
  - https://github.com/diasdavid/webrtc-ring-signaling-server
  - https://github.com/diasdavid/webrtc-chord-signalling-server
  - https://github.com/diasdavid/webrtc-chord-uuid
  - https://github.com/diasdavid/piri-piri.client
  - https://github.com/diasdavid/simple-raytracer
  - https://github.com/diasdavid/dht-id


# Everyone is welcome to participate :)

Feel welcome to open issues with questions, ideas, contribute to the list of endeavours, create a project towards the same goal and discuss potential new ways to make it more interesting.
