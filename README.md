# Colorful Dots Art

## Description

This program uses the Turtle graphics library to create a colorful art piece consisting of randomly placed dots. The colors used are extracted from an image file using the Colorgram package.

## Note

* This code will not work in repl.it as there is no access to the Colorgram package.
* Refer to the video tutorials for more information.

## Usage

* Run the program to generate a colorful art piece.
* The art piece consists of 100 dots, each with a random color chosen from the `color_list`.
* The dots are arranged in a pattern, with each row containing 10 dots.

## Requirements

* Python 3.x
* Turtle graphics library
* Colorgram package (not available in repl.it)

## Code Structure

* The program starts by importing the necessary libraries: `turtle` and `random`.
* It then sets up the Turtle graphics window and creates a Turtle object named `tim`.
* The `color_list` is defined, containing RGB values for each color.
* The program then enters a loop to create the art piece, using `tim.dot()` to create each dot with a random color.
* The dots are arranged in a pattern, with each row containing 10 dots.

## Author

Nadim Anwar
