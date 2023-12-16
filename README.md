# Smash Match Analyzer
### DTSC 3000 Project, James Sprague

This project is a proof of concept for a tool that keeps track of what is happening in a Super Smash Bros Ultimate match based on what we can detect from looking at the game's UI. In the current version of this project, we are detecting what characters the player is using and when a stock is taken in a "Squad Strike" match. (The character the player uses switches after they lose their life.) Data is output into text files, which are then read by our streaming program and displayed on-screen. This includes a file that shows how many points each player has, another file for their currently selected characters, and another file that acts as a log for when a character is switched and how long their life lasted. 

The current version of the model was created in Roboflow, and has separate classes for the first 8 characters in the game. The model has 159 images in total, with roughly 20 images for each character, showing different character costumes, port backgrounds, and stage backgrounds.

Demo Video: https://m.youtube.com/watch?v=-jo6xUL1RRE

Github repo (w/ model and other files): https://github.com/j-sprague/computervision-project-ssbu

![image](https://github.com/j-sprague/computervision-project-ssbu/assets/73149971/394812b2-b5df-4ee2-8f1d-856cfa8a11d9)
