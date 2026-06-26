---
layout: post
title: "Designing My First DLD Project – Parking Counter System"
date: 2026-06-27
permalink: /dld-project/
tags: [semester2, dld, digital-logic, project]
---

# Designing My First DLD Project – Parking Counter System

<img src="/assets/images/dld-project.jpeg"
alt="DLD Parking Counter System"
style="width:100%; border-radius:12px; margin-bottom:20px;">

Among all the projects I worked on during my second semester, the Digital Logic Design project was perhaps the most hands-on and physically demanding experience I had. Building a Parking Counter System using actual hardware components — logic gates, ICs, a breadboard, IR sensors, and a 7-segment display — was a completely different challenge from anything I had done before in software. It pushed me and my teammates to think differently, troubleshoot patiently, and appreciate just how much work goes into making even a simple digital circuit function correctly.

The project was built by a team of three — myself, Ahmed Talib, and Mohsin Riaz. We divided the work as best as we could, but in reality, building a hardware circuit is not something you can easily split into separate pieces. Most of the time, all three of us were gathered around the breadboard together, tracing connections, checking components, and trying to figure out why the circuit was not behaving the way we expected. Working as a team on a physical project taught me a different kind of collaboration — one that required constant communication, patience, and a shared willingness to keep trying.

The core components we used included the IC 74192, which is an up-down counter, the IC 7404 for NOT gate operations, the IC 7432 for OR gate logic, a 7-segment display to show the count, and IR sensors to detect the presence of vehicles. The idea behind the system was straightforward — when a car enters the parking area, the IR sensor detects it and the counter increments, and when a car exits, the counter decrements. The 7-segment display shows the current count at all times. On paper, it made perfect sense. In practice, making it all work together was a completely different story.

The biggest challenge we faced was the sheer number of connections involved. A circuit like this requires precise wiring between multiple ICs, sensors, and display components, and every single connection has to be correct for the circuit to function. One wrong wire, one loose connection, or one component in the wrong pin can cause the entire system to fail — and the hardest part is figuring out exactly where the problem is. We spent days going over our connections, checking each wire against the circuit diagram, and testing individual parts of the system in isolation to identify where things were going wrong.

On top of the wiring, getting the logic right was its own challenge. Combining the counter IC with the gate ICs in a way that correctly responded to the IR sensor inputs required careful thinking about how each component interacted with the others. There were moments where the counter would increment when it should not, or the display would show unexpected values, and we had to trace back through the entire logic to find the source of the error. Those three weeks of working on this project were genuinely stressful at times, but they also taught me more about digital logic than any amount of reading from a textbook could have.

After three weeks of troubleshooting, adjusting, and rebuilding parts of the circuit, the system finally worked. The IR sensor detected input, the counter responded correctly, and the 7-segment display showed the right count. When it all came together, the three of us felt an enormous sense of relief and pride. That moment of seeing the display light up with the correct number after everything we had been through was one of the most satisfying experiences of my entire second semester. It was proof that persistence pays off, and that the most difficult projects often teach the most valuable lessons.

Looking back, the DLD Parking Counter project was one of the defining experiences of my second semester. It taught me how digital logic works in the real world, how hardware circuits are built and debugged, and how to work through frustration as a team without giving up. Ahmed Talib, Mohsin Riaz, and I had put three weeks of genuine effort into that project, and seeing it work made every difficult moment worth it. It was the kind of project that reminds you why engineering is both challenging and deeply rewarding.

---

#MLwithDrBilalAhmad #DrBilalAhmad #MLProject
