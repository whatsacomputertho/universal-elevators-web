# Universal Elevators Game Specification

Universal Elevators is a simulation game inspired by [Lantz & Foddy's Universal Paperclips game](https://en.wikipedia.org/wiki/Universal_Paperclips).  The game begins with a single two-story building whose elevator system the player must control.  As the player transports people, the player earns tips and may purchase upgrades for their building and elevator system.  After the player sufficiently grows their buildings and automates their corresponding elevator systems, the player develops technology to deploy a space elevator.  The space elevator enables cost-effective travel within the solar system, and the game ends when the player has established a colony on mars with its own functioning space elevator.  The player may then watch from the end screen as successful transportation between the Earth and Mars is conducted.

## Progression System

The game progresses through isolated phases in which progression can be controlled by requiring exponential growth targets to be met in order to progress between phases.  The below sections detail the discrete phases composing the game, the upgrades available during each phase, and the upgrades which must be obtained during each phase in order to progress onto the next phase.

### Phase 1: Manual phase

The building begins as a two-story, manually controlled building.  The following is the initial plan for upgrades during this phase.  This phase is still pending testing.

- **Add Floor**
  - Unlocked: After transporting 10 people
  - Requirement: $10 in tips
  - Effect: Adds a floor to the building
  - Limit: Maximum 5 floors during this phase
- **Random Controller**
  - Unlocked: After transporting 100 people
  - Requirement: $20 in tips
  - Effect: The elevator is automatically controlled by randomly choosing a destination floor

### Phase 2: Single building, single automated elevator phase

The building is now automatically controlled.  There are no upgrades planned for this phase yet.

### Phase N: Does not exist

This phase has not been planned yet.