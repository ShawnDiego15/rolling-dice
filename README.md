# rolling-dice
A visualization of rolling pairs of dice, created within a histogram.

Part of Chapter 15 from Python Crash Course by Eric Matthes.

This program uses the Plotly library to simulate rolling various numbers of dice, along with different numbers of sides. The results of a number of rolls are then added to histogram that can be viewed for further data analysis.

This repository contains a number of files:
*die.py* - Contains the class Die, which allows for the creation of die of various sizes.
*die_visual.py* - The main executable file for this program. This file creates instances of Die, rolls them a number of times, and outputs the result into a histogram located in an html file.
*d6.html* - A sample output file, containing the results from a single run of rolling a single 6-sided die a number of times.
*d6_d6.html* - A sample output file, containing the results from a single run of rolling 2 6-sided dice a number of times.
*d6_d10.html* - A sample output file, containing the results from a single run of rolling one 6-sided die and a 10-sided die a number of times.
