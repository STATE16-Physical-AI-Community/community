# Physical AI Failure Taxonomy

This document collects possible failure modes for AI systems operating in or reasoning about the physical world.

## Physical constraint failures

Examples:

- Impossible motion
- Invalid trajectory
- Collision with obstacle
- Violation of speed limits
- Violation of acceleration limits
- Violation of energy or battery constraints

## Operational constraint failures

Examples:

- Entering a restricted area
- Ignoring no-fly zones
- Ignoring mission rules
- Violating system operating procedures
- Selecting an action outside the system authority

## Safety failures

Examples:

- Unsafe distance from humans
- Unsafe distance from infrastructure
- High-risk maneuver
- Failure to stop under uncertainty
- Ignoring emergency constraints

## Sensor-state inconsistency

Examples:

- Estimated state does not match observations
- Generated state contradicts sensor data
- Object appears in the model but not in observations
- Model ignores uncertainty in perception

## Goal-state inconsistency

Examples:

- Action does not support the stated goal
- Plan reaches the wrong target
- Subgoal contradicts mission objective
- Generated trajectory satisfies local constraints but fails the global goal

## World model failures

Examples:

- Latent state does not represent a physically possible configuration
- Predicted future violates dynamics
- Model generates plausible but impossible transitions
- Simulation success does not transfer to real-world constraints
