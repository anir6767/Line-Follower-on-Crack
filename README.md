# Line Follower on Crack

A line-following robot that I'm building from scratch, with the goal of making it fast, precise, and capable of handling complex tracks using PID control.

---

## What is it?

Basically, an LFR, but I want to take it a bit further than the usual Arduino line follower.

The plan is to build a robot that can follow lines smoothly using PID, handle sharp turns, navigate intersections and loops, and hopefully do all of this at pretty high speeds without constantly losing the line.

I'll be starting with a prototype using the hardware I already have, then eventually move on to designing my own PCB and 3D-printing a custom chassis.

The project is still in its early stages, so a lot of things will change as I experiment and figure stuff out.

---

## Why I built this

I've wanted to get into PCB design and 3D design for a while, but I haven't really had a proper project to learn them through.

I also want to understand PID control properly instead of just copying some code from the internet and hoping it works.

So I decided to build an LFR that would force me to learn all three: PCB design, CAD, and PID tuning.

I'm taking some inspiration from projects like [GRUZIK LineFollower 3.0](https://github.com/NYDEREK/LineFollower_GRUZIK3.0), but I'm not trying to clone it. I want to make my own version, figure out the electronics and chassis myself, and learn along the way.

---

## Planned Features

* **PID line following** — Smoothly adjust motor speeds based on sensor readings instead of just turning left or right.
* **Precise movement** — Tune the PID controller to reduce wobbling and make the robot follow the line more accurately.
* **Intersections and loops** — Work on detecting intersections and handling different track layouts without getting confused.
* **Sharp turns** — Try to maintain control through tight corners without flying off the track.
* **Custom PCB** — Design my own PCB in KiCad instead of relying entirely on separate modules.
* **Custom chassis** — Design a chassis in CAD that fits all the components and works well with the robot.
* **Speed tuning** — Once the robot follows the line reliably, push the speed while trying to maintain control.

These are goals for the project, not features that are already finished.

---

## Repository Structure

```text
Line-Follower-on-Crack/
├── README.md
├── prototype/
├── pcb/
├── cad/
└── docs/
```

* `prototype/` — Initial code, wiring, and experiments.
* `pcb/` — KiCad schematic and PCB files.
* `cad/` — Chassis designs and 3D files.
* `docs/` — Development journal, notes, and test results.

I'll add the actual files as I work on each part.

---

## Tools

* Arduino IDE — Writing and testing the code
* KiCad — PCB design
* FreeCAD — 3D chassis design
* GitHub — Keeping track of everything

---

## Current Status

* [x] Created the GitHub repository
* [ ] Build the first prototype
* [ ] Get the sensors working
* [ ] Get the motors working
* [ ] Implement PID
* [ ] Tune the robot
* [ ] Test intersections and loops
* [ ] Design the PCB
* [ ] Design the chassis
* [ ] Put everything together and test it

More updates coming as I make progress.
