# Probability and Network Analysis Project 

## Project Overview

This project involves various statistical simulations, probability calculations, and network analysis exercises. Through these exercises, I have deepened my understanding of probability theory, simulation techniques, and network analysis, while honing my skills in R programming and data visualization using `ggplot2`.

## Learning Outcomes

### Probability and Simulation
1. **Understanding Probability**:
   - I calculated the probability of drawing a club from a standard deck of cards and the probability of drawing a card that is 7 or higher.
   
2. **Custom Function Creation**:
   - I developed a custom R function, `card.draw`, to simulate the random drawing of cards with replacement from a 52-card deck.
   - I implemented error checking within the function to handle invalid input parameters.

3. **Large-Scale Simulations**:
   - I conducted simulations with 1,000,000 random card draws to estimate the distribution of suits and card numbers.
   - I used these simulations to estimate the proportions of specific outcomes, such as drawing a club or a card that is 7 or higher.

4. **Expected Value and Variance Calculation**:
   - I calculated the exact expected value and variance for the number outcomes of a randomly drawn card.
   - I verified these exact values through large-scale simulation.

### Problem-Solving and Strategy
1. **Monty Hall Problem**:
   - I simulated an altered version of the Monty Hall problem, incorporating the possibility of Monty accidentally revealing the car.
   - I analyzed the probabilities of winning when the contestant sticks with their initial choice versus changing their choice.

2. **Casino Game Simulation**:
   - I simulated a casino game where the player rolls a die and has multiple attempts to roll the same number again, unless they roll a 6.
   - I estimated the probability of winning the game through 10,000 iterations.

### Network Analysis
1. **Social Network Analysis**:
   - I analyzed a proximity network of actors living close to each other.
   - I identified the type of network (social network) and determined that it is undirected.
   
2. **Network Object Creation**:
   - I created a network object in R using the `network` package to reflect the proximity relationships.
   - I outputted the adjacency matrix and checked the adjacency of specific actors.
   - I visualized the network with node labels to illustrate the connections.

## Skills Developed

### R Programming
- **Custom Function Development**:
  - I created robust functions with error checking and handling.
  
- **Simulation and Probability Calculation**:
  - I conducted large-scale simulations and probability calculations efficiently.
  
- **Data Visualization**:
  - I utilized `ggplot2` for creating clear and informative visualizations of simulation results.

### Statistical Analysis
- **Expected Value and Variance**:
  - I calculated theoretical expected values and variances and verified them through simulations.
  
- **Problem Solving in Probabilistic Scenarios**:
  - I simulated and analyzed complex probabilistic scenarios, such as the Monty Hall problem and casino games.

### Network Analysis
- **Network Object Manipulation**:
  - I created and manipulated network objects using the `network` package.
  
- **Adjacency Matrix Analysis**:
  - I analyzed adjacency matrices to understand connections within networks.
  
- **Network Visualization**:
  - I visualized networks to better understand and present proximity relationships.

Overall, this project has enhanced my proficiency in R, particularly in the areas of simulation, statistical analysis, and network analysis. It has also strengthened my ability to visualize and interpret complex data, which is essential for any data scientist or analyst.
