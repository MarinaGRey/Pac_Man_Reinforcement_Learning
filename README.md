# Pac-Man Autonomous Agent Projects

Welcome to the repository for our Pac-Man autonomous agent projects! This repository contains two main practice folders: pacman_agent and reports.

This project was awarded first place in the class competition of Machine Learning I at UC3M. In collaboration with María Ángeles Magro Garrote ([GitHub Profile](https://github.com/mariamagro)). Note that only our code has been updated, not all class materials.

## Overview

We had two main projects to complete at class, one using classification and other using reinforcement, and then both results were compared to obtain the best agent.

### Project 1
The aim of Project 1 was to develop an autonomous Pac-Man agent capable of efficiently playing the game and maximizing its score. This involved:
- Selecting and refining various algorithms.
- Creating and testing two distinct models:
  - **Model 1:** Focused on quickly eating ghosts.
  - **Model 2:** Concentrated on maximizing score by including pac-dots.

The **J48 decision tree algorithm** was identified as the most effective for predicting Pac-Man's next move. In contrast, regression models revealed that **M5** was best for predicting future scores. Despite Model 1 having better accuracy, Model 2, which included pac-dots, offered superior overall results in terms of gameplay fluency and scoring.

### Project 2
In Practice 2, the objective was to implement a Q-learning algorithm to enable an autonomous Pac-Man agent to navigate various maze configurations and maximize rewards. Key components included:
- Designing a state representation with direction and distance attributes.
- Setting up a Q-table with 16 states and action columns.
- Adjusting learning parameters like alpha, epsilon, and discount factors.

Significant improvements were achieved by:
- Simplifying the reward function to prioritize eating pac-dots and penalizing wall collisions.
- Developing methods for updating the Q-table, calculating rewards, and determining Pac-Man’s position and nearest elements.

This approach proved more effective than previous models, allowing Pac-Man to optimally eat both ghosts and pac-dots, resulting in higher scores.

## Repository Structure

This repository contains the following folders and files:

### pacman_agent
- It contains all the necessary components to run the final pacman agent we created (note tht it is the reinforcement one). You can create a new Python project and upload the folder to run it through the terminal.

### reports
- It contains the different reports made after each project, with the process and results obtained.
