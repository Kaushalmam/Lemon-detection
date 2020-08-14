# Lemon-detection
This code check if a participant is successfully able to complete a lemon and spoon race or not.

- This code is implemented in Matlab.
- This is a personal project that I did to understand video processing.
- Each video suppiled to the code is broken down into frames.
- Within each frame, the lemon is detected.
- We keep a track of the position of lemon and track its trajectory.
- If the lemon is detected to be progressively moving towards south and eventually disappearing from the frame then it is termed to be an unsuccessful attempt.
- If the lemon is tracked to be progressively moving in the forward direction then the attempt is marked successful.
