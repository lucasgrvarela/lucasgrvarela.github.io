+++
title = 'Doing SRE the right way!'
date = 2023-09-30T01:10:00-03:00
draft = false
tags = ["sre", "site reliability engineer"]
+++

We use to call SREs as the Guardians of Production, they are always vigilant to be sure the systems will be in place and available for the customers to be used.

As Google said in their SRE Book "Reliability Is the Most Important Feature", because no other feature matters if your system is down and the user can't perform any action at it.

To ensure a great reliability your system needs to tolerate failure, it's inevitable your systems will fail, you can't have 100% availability all the time, it's almost impossible and too costly. 

The difference between a good system and a bad one is how fast can you detect the failure (Mean Time to Acknowledge - MMTA) and how fast can you recover for it (Mean time to Recovery - MTTR).

Based on your business availability requirements some Goals can only be reached through automations, you can't rely on humans doing the detection and recovery by hand, on some cases having an Playbook on how to investigate/mitigate/solve the issue is already enough, the maturity of your company, how much money and time you can put into the Reliability is the difference between achieving a fully automated setup or a manual one.

to be continued...
