# CS230

This repository holds the software design document I created for The Gaming Room in CS 230. Below are my reflections on the project.

## Summary of the client and their requirements

The Gaming Room was the client. They own a game called Draw It or Lose It that currently runs only as an Android app. They wanted me to design a web-based version of the game that works across multiple platforms, including Android, iOS, Windows, Mac, and Linux. The design also had to keep game, team, and player names unique and make sure only one game environment exists in memory at a time.

## What I did well

I did a good job keeping the document clear and easy to follow. I broke the requirements down into simple parts and explained the design choices in plain language so both the client and the development team could understand them. I also kept the technical sections tied directly to the client's actual needs.

## What was helpful about the design process

Working through the design document first helped me understand the problem before writing any code. Planning the classes and how they connect made the code easier to write because I already knew how the pieces fit together. It saved time and helped me avoid mistakes later.

## How I interpreted and met the user's needs

I read the client's requirements and turned each one into a specific design decision. For example, the need for one game environment in memory led to using the singleton pattern, and the need for unique names led to checking names before creating a new game, team, or player. Considering the user's needs is important because software is only useful if it actually solves the user's problem. If you ignore those needs, you can build something that works but does not help anyone.

## How I approached the design

I started by understanding the requirements, then planned the structure before coding. I used object-oriented design ideas like inheritance and design patterns to keep the code organized. In the future, I would use the same approach: study the requirements first, sketch out the classes and how they relate, and review the design before writing code.
