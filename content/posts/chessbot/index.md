---
title: Chess Bot
date: 2022-10-09
draft: False
description: "What if your chess board could roast you"
summary: "What if your chess board could roast you"
series: ["Mags, Chess Robot"]
series_order: 1
---

I want to make a chess board that can move pieces by itself. The pieces would have magnets embedded in them, and an electromagnet would make them move from beneath the board. 

Think about it. You play a move, and then the board plays the best move possible against you. You can never win. It's utterly hopeless. And when it beats you, it says, "Looks like I beat you. High five!"

Other cool things made possible by a robotic board include playing against people online over-the-board, automatically record the moves of games you play over-the-board, and voice-controlled moves (for example, you could play blindfold chess).

I'm applying to [ProjX](https://projx.mit.edu/) for up to $500 in funding.

## Research
First, I researched what kind of robotic chess boards already exist. They do in fact exist, but they all leave something to be desired. 

 - [SquareOff](https://squareoffnow.com/) This product works, but it's expensive and inconsistent (the pieces are detected by the flexing of the board). 
 - [Regium Chess](https://www.facebook.com/watch/?v=794043774452044) Big kickstarter campaign that was a [complete scam](https://lichess.org/blog/XlE48hEAACIAQv2F/regium-extraordinary-claims-require-extraordinary-evidence)
 - [Phantom](https://www.kickstarter.com/projects/wondersubstance/phantom-the-most-advanced-chess-board-in-the-world) A suspected scam, but they actually built a working prototype

These are the best resources I could find:
 - [Instructables Project](https://www.instructables.com/Automated-Chessboard/), a simple but effective build with good documentation
 - [Phantom](https://hackaday.io/project/179268-automatic-chessboard), the suspected scam built a prototype and documented it on hackaday.

## Pieces
Making pieces is the first priority. I could buy a set and modify them, but making custom wood pieces is so much cooler. For fun, I made this pawn on the [Hobby Shop's](https://studentlife.mit.edu/hobbyshop) manual lathe.
![Pawn](images/pawn.jpg)

For the actual set, I want to use the Hobby Shop's 4-axis wood router, but first I have to get good at CAM. The pieces will have magnets and weights embedded in the bottom.

The squares need to be wide enough for pieces to move in between each other.

## Electronics
I'll detect pieces using reed switches (like the instructables project). This tells me which squares are occupied, but not what pieces are on them. I'll have to keep track of where each piece has moved, based on their known starting positions.

I'm thinking of using a teensy 4.1 as the processor and TMC2209 stepper drivers, but I need to research this more.

## Gantry
After I get the prototype working, I'll add a gantry to move the electromagnet around. I think I'll copy CoreXY 3D printers for this. Among many other things, I'll have to decide whether to use linear bearings, linear rails, or v-rollers (I hate these with a burning passion).

## Clock
My ultimate goal is to integrate a nice chess clock into the board. This would have clicky switches like the awesome [Chronos clocks](https://www.amazon.com/US-Chess-Federation-Chronos-Digital/dp/B012B9YPC6/ref=sr_1_3) and a touch display. 
