# Hand-Gesture-
How it works:

Captures video from the webcam and flips it for a mirror view.

Uses MediaPipe Hands to detect hand landmarks.

Tracks the index fingertip (landmark 8) to move the mouse cursor.

Tracks the thumb tip (landmark 4) to measure its vertical distance from the index finger.

If the thumb and index finger are close together (dist < 20), it simulates a mouse click.

Displays the webcam feed with hand landmarks drawn for visual feedback.
