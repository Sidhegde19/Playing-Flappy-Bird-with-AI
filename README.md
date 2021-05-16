# Playing-Flappy-Bird-with-AI

This project follows the discription of the Neuroevolution of Augmentation Topolgoies (NEAT) algorithm demostrated on a popular game Flappy Bird.

I fascinated by [Code Bullet's video](https://www.youtube.com/watch?v=WSW-5m8lRMs) on this and decided to try it out by myself. When I say myself, I did take reference from [Tech With Tim Video](https://www.youtube.com/watch?v=MMxFDaIOHsE&list=PLzMcBGfZo4-lwGZWXz5Qgta_YNX3_vLS2) implementing and demostrating this project.

## What is NEAT?

First of all, I think it's a pretty neat name for an algorithm. 

According to Wikipedia, NeuroEvolution of Augmenting Topologies (NEAT) is a [genetic](https://en.wikipedia.org/wiki/Genetic_algorithm) algorithm aimed for the generation of artificial neural networks. This was developed by Ken Stanley in 2002 while at The University of Texas at Austin.

The weighting parameters and structures are altered in order to find a balance between the fitness of evolved solutionas and their diversity. 

There are three key techniques:
1. Tracking genes with history markers to allow crossover among topologies
2. Applying speciation (the evolution of species) to preserve innovations
3. Developing topologies incrementally from simple initial structure

## How did I implement it?

To enable evolution in better sense:
1. I used a multiple birds
2. I assigned each of them some fitness points 
3. I also used generation of the birds

Initially multiple birds start flying at the random point as they go through pipes, the number of birds decrease with the bird who flew the longest having the most fitness. As this algorithm is evolutionary and supports "Survival of the Fittest", the next generation of birds will be modelled after the fittest bird.

Through multiple generations, the birds will get fitter and go thorough more pipes and at some point it will be a perfect run of flappy bird game.

## References 

1. I could have done it without [Time's Video](https://www.youtube.com/watch?v=MMxFDaIOHsE&list=PLzMcBGfZo4-lwGZWXz5Qgta_YNX3_vLS2). So huge thanks to him.
2. [Code bullet's video](https://www.youtube.com/watch?v=WSW-5m8lRMs)
3. [Information of NEAT by Wikipedia](https://en.wikipedia.org/wiki/Neuroevolution_of_augmenting_topologies)
