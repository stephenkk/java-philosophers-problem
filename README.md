# java-philosophers-problem

This is a group project for Lehman College CMP 697 Fundamentals of Operating Systems, Fall 2018. The Dining Philosophers' problem is a classic exercise in Computer Science to demonstrate deadlocks and how to prevent them. The problem is to simulate five philosophers sitting around a circular table, with one chopstick in between each philosopher and her neighbor. (five total chopsticks) Philosphers can either eat or think. After she stops eating, the philospher will think for a random amount of time until she gets hungry. In order for her to eat, a chopstick must be available for her to pick up at either one of her sides (i.e. neither of her neighbors on her left or right is currently eating).

This solution uses the Java modifier synchronized to protect the pick_up_sticks(), which is the critical section.
