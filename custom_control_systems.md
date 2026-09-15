# Custom Control System Guidelines
This document outlines guidelines to help get a custom control system approved. Meeting every guideline does not guarantee approval.

Approvals are based on several factors, including but not limited to:

 - Builder experience

 - System testing

    - Especially testing in active combat

 - System documentation and clarity

 - Bot dangerousness

C.R.O.W. supports innovation and development, and we will work with builders to get custom systems approved when possible. However, time and resource availability cannot be guaranteed.

## General Rules
Any custom system must comply with all rules. No exceptions will be given. This applies particularly to correct failsafing (all motors must stop when transmitter power or signal is lost).

Builders should ensure their code cannot get stuck or crash in a way that prevents failsafing.

## Frequency
Systems should be capable of using more than one frequency to prevent collisions with other robots. Digital spread spectrum or frequency hopping is preferred.

Builders must comply with Australian laws regarding allowed frequencies and transmission power.

## Connection Timeliness
Robot combat events run on a tight schedule, and we do not have time for connection difficulties. Builders should engineer systems to connect reliably and quickly, without needing to contact the robot once it is powered up (which occurs before the transmitter is turned on).

If connections take longer than 30 seconds, you may forfeit a fight. If a connection drops mid‑match and causes a loss, this will not be grounds for a replay.

## Interference
Systems that unintentionally interfere with other radios will not be approved. If interference is confirmed during an event, results may be reversed if it is deemed a major factor.

## Wi‑Fi and Bluetooth
While these can form the basis of safe and effective communication systems, they are typically not suitable. Care should be taken if choosing to base a system on them. It is unlikely that a robot with a spinner controlled by Wi‑Fi or Bluetooth will be approved.