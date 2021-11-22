# Robot Command

## Prompt

You will write a program to interactively control a robot by issuing commands via the terminal.

Working in pairs, you will develop a program that includes these elements:

* The program controls actions and sounds in the robot.
* The program prints a prompt that lists the possible actions.
* The robot can perform at least ten different commands.
  * The command to quit may be counted as one of these ten different commands.
  * Each action (except, perhaps, the command to quit) must be implemented as a separate procedure
  * At least five of the procedures should utilize parameters in a substantive way; if user values are requested, the input/output should be handled in a separate procedure and values passed to the procedure controlling the action.
  * At least two actions should be blocking and at least two actions should be non-blocking
* The program ends only after the user types a command to quit.
* The program counts the number of actions taken and prints the number of actions taken after the user types a command to quit.

Command requirements:
* Commands should be words, not letters.
* Each command must perform an obviously distinct action. The same action, but with different duration or speed does not count as a different action. For example, turnLeft and turnRight might be allowed, but turnLeft1second, and turnLeft2seconds would not be considered distinct.
* At least 5 commands must also take one or more parameters, entered in a helper function and passed to the function executing the command. For example, if you implement the beep function, the user must be able to specify the duration and pitch of the beep. If you implement a short dance, the user may not need to specify the length of any of the dance steps.

## Response
The program is [here](https://github.com/ridhika123/Robot-Command/blob/main/robot-command.c).
