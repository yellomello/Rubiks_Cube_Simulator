# Rubik's Cube Simulator

Welcome to the Python simulator for a Rubik's Cube! This simulator allows you to interact with and manipulate the Rubik's Cube using a set of predefined moves. Whether you're a Rubik's Cube enthusiast looking to test algorithms or a data scientist training a Reinforcement Learning model, this simulator is here to assist you.

## Default Cube Configuration

The default configuration of a solved cube is represented in the `main` dictionary with the following structure:

```python
main={
    'White':   [[1,2,3], [4,5,6], [7,8,9]],
    'Blue':    [[10,11,12], [13,14,15], [16,17,18]],
    'Orange':  [[19,20,21], [22,23,24], [25,26,27]],
    'Green':   [[28,29,30], [31,32,33], [34,35,36]],
    'Red':     [[37,38,39], [40,41,42], [43,44,45]],
    'Yellow':  [[46,47,48], [49,50,51], [52,53,54]],
}
```

Feel free to explore and modify the default cube configuration as needed.

## Available Moves

The simulator provides a set of predefined moves for manipulating the Rubik's Cube:

### Right and Left

- `right_up()`: Rotate the right side clockwise.
- `right_down()`: Rotate the right side counterclockwise.

- `left_up()`: Rotate the left side clockwise.
- `left_down()`: Rotate the left side counterclockwise.

### Up and Down

- `up_left()`: Rotate the top (up) side counterclockwise.
- `up_right()`: Rotate the top (up) side clockwise.

- `down_left()`: Rotate the bottom (down) side counterclockwise.
- `down_right()`: Rotate the bottom (down) side clockwise.

### Front and Back

- `front_left()`: Rotate the front side counterclockwise.
- `front_right()`: Rotate the front side clockwise.

- `back_left()`: Rotate the back side counterclockwise.
- `back_right()`: Rotate the back side clockwise.

## Getting Started

Feel free to run the program and test your algorithms using the provided moves. Modify the cube's configuration or implement your own algorithms to see how the Rubik's Cube responds.

## Reinforcement Learning

The simulator is a valuable tool for training Reinforcement Learning models to solve the Rubik's Cube. If you're working on such a project, this simulator provides a convenient environment for experimentation and training.

Happy coding, and may your Rubik's Cube-solving endeavours be successful!
