![Close Encounters of the Third Kind](https://github.com/user-attachments/assets/2ff4ac0c-9e7d-4783-a3c9-985939711c18)

> Interactive light board with a 5x6 grid of cells, where each cell can display various colors.

#

This Pygame program creates an interactive light board with a 5x6 grid of cells, where each cell can display various colors. The grid is rendered based on cell dimensions of 220 pixels wide and 100 pixels high, resulting in a window size of 1100x600 pixels. The program defines several color patterns and uses these patterns to update the grid based on user input. The colors include black, white, green, yellow, purple, orange, and pink, providing a vibrant and dynamic visual experience.

The primary functionality of the program includes the ability to apply predefined patterns to the grid and play corresponding sound effects. Users can activate different patterns by pressing keys (1 through 6) on the keyboard, with a random sequence of pattern triggered with the '6' key. Each pattern is associated with a distinct sound effect, which plays when the pattern is displayed. This feature enhances the interactive experience by combining visual and auditory feedback.

The code uses Pygame’s drawing functions to render each cell of the grid with the specified color. It employs a straightforward event loop to handle user inputs, including key presses and releases. When a key is pressed, the program updates the grid with the selected pattern and plays the related sound. Upon releasing a key, the grid is cleared, and any currently playing sound is stopped. This ensures that the grid updates are responsive to user interactions.

To address potential visual issues, such as bottom padding space, the code dynamically adjusts the grid height to ensure it matches the window height precisely. This adjustment eliminates any unwanted padding or spacing, resulting in a perfectly aligned grid. The program’s design effectively balances functionality and aesthetics, providing a well-integrated and engaging interactive light board experience.

#

https://github.com/user-attachments/assets/656a81b6-7319-404e-8045-a7e4e7ac8a8a

#

#
### Related Links

[Alien Life](https://github.com/sourceduty/Alien_Life)
<br>
[UFO Traffic Light](https://github.com/sourceduty/UFO_Traffic_Light)

***
Copyright (C) 2024, Sourceduty - All Rights Reserved.
