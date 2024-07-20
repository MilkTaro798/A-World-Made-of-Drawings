# A World Made of Drawings

![Screenshot](https://github.com/MilkTaro798/A-World-Made-of-Drawings/blob/main/screenshot1.png)

## Overview

This project, inspired by the 1955 children's book "Harold and the Purple Crayon" by Crockett Johnson, brings Harold's magic to the computer screen. It implements portions of the paper "Harold: A World Made of Drawings" presented at ACM NPAR 2000.

In this application, users can:

1. Draw hills and valleys on the ground
2. Create strokes in the sky
3. Draw billboards that appear on top of the ground

## Key Features

- 3D mesh editing operations in response to user input
- Conversion of 2D screen space coordinates to 3D virtual world using pick rays and intersection tests
- Implementation of computer graphics algorithms described in research papers

## Technologies Used

- TypeScript
- WebGL
- Three.js

## Implementation Highlights

- Mouse-sky interactions for creating strokes in the sky
- Ground editing algorithm to create hills and valleys
- Dynamic camera height adjustment based on ground elevation
- Billboard creation and manipulation

## Learning Outcomes

Through this project, I gained experience in:

- 3D graphics programming
- Ray casting and intersection tests
- Mesh manipulation and editing
- Implementing research paper algorithms

## Installation and Running

1. Clone the repository
2. Install dependencies with `npm install`
3. Run the project with `npm run start`
4. Open a web browser and navigate to `http://localhost:8080`

## Acknowledgments

This project was completed as part of CSCI 4611 Fall 2022 at the University of Minnesota. The original assignment was based on content by Daniel Keefe and adapted by Evan Suma Rosenberg.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.