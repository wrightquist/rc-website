+++
images = [""]
author = "Staff"
description = ""
date = "2021-12-03T00:00:00-05:00"
title = "Rivanna Maintenance: December 14, 2021"
# url = "/maintenance"
draft = false
tags = ["rivanna"]
categories = ["feature"]
+++

{{< alert-green >}}Rivanna will be down for maintenance on <strong>Tuesday, December 14, 2021</strong>, beginning at 6 a.m.{{< /alert-green >}}

You may continue to submit jobs until the maintenance period begins, but if the system determines your job will not have time to finish, it will not start until Rivanna is returned to service.

Rivanna is expected to return to service by .

## IMPORTANT MAINTENANCE NOTES

### Modules

1. The following software modules will be **removed** from Rivanna during the maintenance period:
    - tensorflow/1.12.0-py27, 2.0.0-py36

2. The following **upgrades** will take place during the maintenance period.
    - gromacs/2021.2 - with GPU support; please load `goolfc` first
   Upgrades to default versions of applications:
    - salmon/1.2.1 -> 1.5.1

3. **New** modules:
    - [alphafold/2.0.0](/userinfo/rivanna/software/alphafold) - DeepMind's protein structure prediction
    - deeplabcut/2.2 - animal pose estimation
    - [namd/2.14](/userinfo/rivanna/software/namd) - Nanoscale Molecular Dynamics
    - vmd/1.9.4 - Visualization software for NAMD
    - ocaml/3.12.1
    - pov-ray/3.7.0 - 3D graphics with raytracing
    - unrar/6.0.2