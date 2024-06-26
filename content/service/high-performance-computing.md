+++
categories = [
  "services",
  "hpc",
]
tags = [
  "hpc",
  "ivy",
  "rivanna",
]
draft = false
date = "2020-04-16T09:30:12-05:00"
title = "High Performance Computing"
description = ""
author = "RC Staff"
images = [
  "",
]

+++

<p class=lead>Research Computing supports all UVA researchers who are interested in writing code to address their scientific inquiries. Whether these programming tasks are implemented interactively, in a series of scripts or as an open-source software package, services are available to provide guidance and enable collaborative development. RC has specific expertise in object oriented programming in <b>Matlab</b>, <b>R</b>, and <b>Python</b>.</p>

Examples of service areas include:

- Collaborating on package development
- Reviewing and debugging code
- Preparing scripts to automate or expedite tasks
- Developing web interfaces for interactive data exploration
- Advising on integration of existing software tools

- - -

<p class=lead>UVA has two local computational facilities available to researchers: <b>Rivanna</b> and <b>Ivy</b>. Depending upon your use case, privacy requirements, and the application(s) you need to run, we can help you create an account and start processing your data.</p>

<div class="card" style="margin:2rem;">
  <div class="card-block">
    <h2 class="card-title">Rivanna</h2>
    <h5 class="card-subtitle mb-2">Standard Security HPC Cluster</h5>
    <p class="card-text">
    Rivanna provides a high-performance computing environment for all user levels with a total of {{< rivanna-node-count >}} nodes and {{< rivanna-core-count >}} cpu cores.  This includes specialty hardware like GPGPUs and large memory nodes. All nodes are supported by a high-performance EDR/FDR Infiniband network using Mellanox hardware. The Rivanna cluster also provides approximately {{< rivanna-scratch-capacity >}} of scratch (temporary) storage on a high-speed Lustre filesystem. Users may also lease space on “Research Project” and “Research Standard” storage that are mounted to Rivanna, as well as elsewhere. 
    </p>
    <a href="/userinfo/hpc/overview" class="card-link"><button class="btn btn-warning">Read more about Rivanna</button></a>
  </div>
</div>

<div class="card" style="margin:2rem;">
  <div class="card-block">
    <h2 class="card-title">Ivy</h2>
    <h5 class="card-subtitle mb-2">High-Security / HIPAA Computing Environment</h5>
    <p class="card-text">
    Ivy is a secure computing environment for researchers consisting of virtual machines (Linux and Windows) backed by a total of {{< ivy-node-count >}} nodes and approximately {{< ivy-core-count >}} cpu cores. Researchers can use Ivy to process and store sensitive data with the confidence that the environment is secure and meets HIPAA, FERPA, CUI or ITAR requirements.
    </p>
    <a href="/userinfo/ivy/overview" class="card-link"><button class="btn btn-warning">Read more about Ivy</button></a>
  </div>
</div>

