# Universal Elevators Game Specification

Universal Elevators is a simulation game inspired by [Lantz & Foddy's Universal Paperclips game](https://en.wikipedia.org/wiki/Universal_Paperclips).  The game begins with a single two-story building whose elevator system the player must control.  As the player transports people, the player earns tips and may purchase upgrades for their building and elevator system.  After the player sufficiently grows their buildings and automates their corresponding elevator systems, the player develops technology to deploy a space elevator.  The space elevator enables cost-effective travel within the solar system, and the game ends when the player has established a colony on mars with its own functioning space elevator.  The player may then watch from the end screen as successful transportation between the Earth and Mars is conducted.

## Minimally Viable Product

To implement a minimally viable product, or minimally playable game, I intend to implement a system satisfying the following
1. The user has exactly one building, and starts by controlling its elevator system manually
2. People should decide to leave a tip according to a bernoulli distribution
3. The amount of people's tips should be decided according to a binomial distribution
4. The user can use accrued tips to buy new floors and new elevators
5. Before being able to buy a second elevator, the user must buy an auto-controller upgrade
6. The auto-controller upgrade gives the user a RandomController, which they must upgrade over time to behave more rationally
7. The cost of new floors and elevators increases as the user buys them, as do auto-controller upgrades