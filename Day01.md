## Blockly Maze Completion
After you complete the 10th level, what is the JavaScript code you got? 
Cut and paste and assign it to the variable level_10_code.

How many blocks did you have left? 
Assign it to the variable remaining_blocks.



level_10_code = '''while (notDone()) {
  moveForward();
  if (isPathForward()) {
    if (isPathRight()) {
      turnRight();
    } else {
      if (isPathLeft()) {
        turnLeft();
      }
    }
  } else {
    if (isPathLeft()) {
      turnLeft();
    } else {
      turnRight();
    }
  }
}
}
 '''
remaining_blocks =  0
print("JavaScript code for Level 10")
print(level_10_code)
print("Number of blocks remaining", remaining_blocks)
