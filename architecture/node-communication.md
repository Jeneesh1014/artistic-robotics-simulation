# Node Communication

The project currently uses three ROS2 nodes.

1. Speech-to-text node

Receives voice input and converts it into text commands.

2. Parser node

Processes text commands and extracts drawing information.

3. Planner node

Controls robot movement based on parsed instructions.

Communication between nodes happens through ROS2 topics using publisher/subscriber architecture.

Workflow:

Voice Input
→ Speech Node
→ Parser Node
→ Planner Node
→ Robot Movement
