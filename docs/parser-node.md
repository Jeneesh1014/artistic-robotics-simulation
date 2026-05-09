# Parser Node

The parser node receives text commands from the speech-to-text node and converts them into structured drawing instructions.

Example:

Input:
"draw a big square"

Output:
shape = square
size = big

The parser node publishes structured messages that are later used by the planner node for robotic movement.

Current implementation uses keyword-based parsing for learning purposes.

Responsibilities of the parser node:

- receive speech text
- identify shape names
- identify size parameters
- create structured output messages
- publish commands to the planner node
