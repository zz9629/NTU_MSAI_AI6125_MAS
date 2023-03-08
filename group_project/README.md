# Contents
AI6125: Multi-Agent System
- Materials: project materials
- Submission: my project report and source code

# Build Intelligent Agents for Tileworld Environment
## OBJECTIVES
The purpose of this project is to:
-  Make students familiar with a popular toolkit for the modelling and simulation of agent-based systems.
-  Provide students the opportunity to experiment with different agent designs for a popular agent- based testbed.

## SPECIFICATION
The aim of this exercise is to use the MASON agent toolkit (Java-based tool) to implement an agent which can inhabit and perform in the provided Tileworld system. You are free to implement any type of agent you desire using any algorithms you would like. This will be conducted in teams of 3-4 students, with each team member designing and implementing one agent. Your agent team (3-4 agents) will then perform together in the same Tileworld.

### MASON
MASON is a widely used, open-source, cross-platform, agent-based modelling and simulation toolkit that was originally developed at George Mason University. It is written in Java and has extensive online tutorials and examples. Before the implementation, it is recommended that you spend some time going through the manual of MASON (Section 1.1 and Section 2.1-2.12) yourself. The manual and other related materials can be obtained from the following link: https://cs.gmu.edu/~eclab/projects/mason/. By reading the recommended sections of the manual, you should have a basic understanding of the architecture of MASON and its working flow.

### Tileworld
In this project, you will use Tileworld as a canonical reference for an agent-based model to implement. Tileworld is a chessboard-like grid on which there are agents, tiles, obstacles, holes, and a fuel station. See Figure 1 for an example.
- An agent is able to move up, down, left or right, one cell at a time.
- A tile is a unit square which can be carried by the agent.
- An obstacle occupies a grid cell and is immovable, agents cannot occupy the same cell as an obstacle.
- A hole is a grid cell which can be filled in by a tile.
- The fuel station is a grid cell where agents can refuel.
- The reward is obtained by: when the tile is moved on top of the hole cell, the tile and hole cell disappear, which leaves a blank cell. This means a hole is filled and the agent gets a reward.

In this project, you have to develop an agent for the Tileworld domain. We have uploaded two papers about the Tileworld domain to NTULearn, i.e. “A history of the Tileworld agent testbed” and “Introducing the Tileworld: Experimentally evaluating agent architectures”. You may study them to gain a better understanding about the domain.

![The Tileworld example](https://github.com/zz9629/NTU_MSAI_AI6125_MAS/tree/main/group_project/Materials/tileworld.png)

More project details in **material** file.