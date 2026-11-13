# The original OTO

OTO began as a senior capstone project: an automated whiteboard cleaner. See [the original repo](https://github.com/Keem-tt/OTO-Whiteboard-Cleaner).

## What’s in it

- STL files for the printed parts: rack segments, pinion, pod, cleaning arm, mounts, covers, tabs, and rail parts.
- Arduino code for stepper motion, calibration, limit-switch travel bounds, and button-driven clean modes.
- The capstone report: the problem, the requirements, the tradeoffs, the cost targets, the modular rack, and the iteration history.
- The lessons: gear alignment, weight balance, overtravel, and mechanism integration.
- Media from the prototype.

## How it worked

A stepper motor, on a TMC2209 driver, drove the rack-and-pinion rail. Mechanical limit switches set the travel. Push buttons started each clean mode. The parts were printed in PLA+.

## What v2 asks

- Which parts of the rack-and-pinion approach are worth keeping?
- Which parts should be printed, and which should be off-the-shelf?
- Which printed parts were too bulky, too slow to print, or too hard to service?
- How should pad replacement and cleaning pressure be handled earlier in the design?
- Can it be faster, cheaper, and sleeker without losing repairability?
- What needs to be measured again?
