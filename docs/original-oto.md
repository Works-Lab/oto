# Original OTO Reference

Original repo: [Keem-tt/OTO-Whiteboard-Cleaner](https://github.com/Keem-tt/OTO-Whiteboard-Cleaner)

The first OTO was a senior capstone automated whiteboard cleaner. It is useful context for OTO v2 because it already captured a working direction, real printed parts, embedded control code, and a formal project report.

## What The Original Repo Contains

- STL files for printed parts such as rack segments, pinion, pod, cleaning arm, mounts, covers, tabs, and rail-related parts.
- Arduino code for stepper-driven motion, calibration, limit-switch travel bounds, and button-driven clean modes.
- A capstone report covering the original problem statement, requirements, tradeoffs, cost targets, modular rack direction, and iteration history.
- Media from the original prototype.

## Original Architecture

The original OTO direction used a rack-and-pinion rail, a stepper motor, a TMC2209 driver, mechanical limit switches, and a push-button interface.

The report documents a working prototype area, prototype cost, modular expansion concept, printed PLA+ parts, and lessons from gear alignment, weight balance, overtravel, and mechanism integration.

## What Carries Into OTO v2

OTO v2 starts from those lessons, but it should not copy the first architecture blindly.

Useful questions for v2:

- Which parts of the rack-and-pinion approach are still worth keeping?
- Which printed parts became too bulky, too slow to print, or too hard to service?
- How should pad replacement and cleaning pressure be handled earlier in the design?
- Can the same core idea become faster, cheaper, and sleeker without losing repairability?
- What needs to be measured again instead of assumed from the capstone prototype?
