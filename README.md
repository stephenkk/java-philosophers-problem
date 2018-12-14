# java-philosophers-problem

This is a group project for Lehman College CMP 697 Fundamentals of Operating System, Fall 2018. The Dining Philosophers' problem is a classic exercie in Computer Science to demonstrate deadlocks and how to prevent them. The problem is to simulate five philosophers sitting around a circular table, with one chopstick in between each philosopher and her neighbor. (five total chopsticks) Philosphers can either eat or think. After she stops eating, the philospher will think for a random amount of time until she gets hungry. In order for her to eat, a chopstick must be available for her to pick at either one of her sides (i.e. neither one of her lefthand or righthand neighbor is eating).

This solution uses the Java modifier synchronized to protect the critical section.
