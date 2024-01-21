This is a python simulator for a Rubik's Cube. 

The default values of a solved cube are as follows. 
main={
    'White':   [[1,2,3], [4,5,6], [7,8,9]],
    'Blue':    [[10,11,12], [13,14,15], [16,17,18]],
    'Orange':  [[19,20,21], [22,23,24], [25,26,27]],
    'Green':   [[28,29,30], [31,32,33], [34,35,36]],
    'Red':     [[37,38,39], [40,41,42], [43,44,45]],
    'Yellow':  [[46,47,48], [49,50,51], [52,53,54]],
    }

Moves: 
#Right and Left
right_up()
right_down()

left_up()
left_down()

#Up and Down
up_left()
up_right()

down_left()
down_right()

#Front and Back
front_left()
front_right()

back_left()
back_right()

Feel free to run the program and test your algorithms.

I'm currently trying to train a Reinforcement Learning Model to solve this cube. 

