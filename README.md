# Dataset Sample of the PeRoI Dataset

The provided CSV is a 200-point sample from the original dataset.

The structure of the CSV is as follows:

- Frame_Number: Time frame in epochs
- Pedestrian_ID: Unique ID of the pedestrian
- X_Position: X position of the pedestrian based on real-world coordinates (in metres)
- Y_Position: Y position of the pedestrian based on real-world coordinates (in metres)
- Distance_Increment: Distance of the current step from the previous step (in metres)
- Robot_Presence: Boolean to indicate if robot was present in the scene (1 - True, 0 - False)
- Robot_Type: The type of robot used during this scene (Go1, HSR, MPO700)
- Robot_Influence: Behavior of pedestrian towards robot (attraction, neutral, avoidance)
- X_Robot: X position of the robot based on real-world coordinates (in metres)
- Y_Robot: Y position of the robot based on real-world coordinates (in metres)
