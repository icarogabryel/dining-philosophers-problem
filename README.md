# Dining Philosophers Problem

## Introduction

The dining philosophers problem is a classic synchronization problem that is used to illustrate the challenges of avoiding deadlocks.

## The Problem

The given problem is: Dijkstra, Tanenbaum, Torvalds, Stallman, and Hoare are in a round table too drunk after very intense night out (Don't let be fooled, their age is not a problem when we're talking about being a danger on the dance floor). As every other drunk, in some point they just began to philosophize (yeah, Linus, of course Linux life style is cool and badass...). After a while, they got hungry and decided to eat some spaghetti. The problem begins when they realize that only have 5 forks to eat (Dammit, Stallman, you should have more if you tried to get some cash in your work). Five forks for five people shouldn't be a problem, right? But they are so drunk, they can't get the spaghetti with one fork. So, they need to get two forks to eat. Torvalds is the first to pick a fork (the spaghetti os not a repo but he wants to fork'it so bad). When he tries to get the second one, he realizes that Tanenbaum pick it first (It was on purpose, My mate Baumbaum don't like Linus very much). So, Linus needs to wait for Tanenbaum to finish to eat. But, Tanenbaum is waiting for Hoare to finish. Hoare was quick and pick the other fork of Andrew. Stallman pick the other fork of Hoare and Dijkstra pick the other fork of Stallman (because it was free, open source and have no intention to profit over the fork). Now, Dijkstra is waiting for Linus to finish. Linus is waiting for Tanenbaum to finish. Tanenbaum is waiting for Hoare to finish. Hoare is waiting for Stallman to finish. And Stallman is waiting for Dijkstra to finish. And they are all waiting for the forks to be free. Deadlock.

## The Solution

Instead of buying more forks (Stallman don't like profitable stuff - sound a little communist to me) or just wait for the other to finish (they are drunk, they can't wait), they f\*\*\*ing stole a traffic light from the street and put it on the table. They use the semaphore to control.
