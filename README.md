## Fish & Shark Ecosystem
short description of your chosen predator-prey ecosystem 

## Roles
### Algae (Food of Prey)
Represented as a brown-ish patch in the model. In the initial setup of the model, the algae are spread randomly in the environment. Once eaten by a fish, the algae will regrow after the set algae regrowth time. Patches with no algae during the initial setup will also grow algae with respect to the algae regrowth time. Thus, if there are no fish, the environment will be fully populated by algae.

### Fish (Prey)
Initially, every fish has their own amount of energy (between 0 and 19). Fish can eat algae in the environment to replenish their energy by an amount (between 0 and 19). When they move, it will cost them 1 energy. A fish will die when it loses all its energy. Fish will also reproduce once they mate - this happens when they meet each other on a patch. The reproduction depends on the probability set by the user. When reproducing, each fish produces 3 offsprings and the energy of the parent is divided between the parent and offsprings.

### Shark (Predator)
Initially, every shark has their amount of energy (between 0 and 19) as well. Upon moving, sharks lose energy, and when all energy is lost, a shark dies. To regain energy, the shark will have to eat fishes and then its energy is replenished by an amount (between 0 and 19). Similar to the role of the fish, sharks will be able to reproduce by mating and the reproduction process depends on the probability set by the user. When reproducing, each shark produces 1 offspring and the energy of the parent is divided between the parent and offsprings.
