Seesaw Simulation
📜 Description
This project is a simple, interactive seesaw simulation built using HTML, CSS and JavaScript. Users can click on the seesaw plank to drop randomly generated weights and the simulation dynamically calculates and updates the plank's tilt angle based on torque.

The project is designed to demonstrate basic physics principles (torque = force x distance) and DOM manipulation.

✨ Features
Interactive Weight Dropping: Click anywhere on the plank to drop the "Next Weight" shown on the scoreboard.

Physics Simulation: Torque is calculated based on each weight's mass and distance from the pivot, updating the plank's rotation (clamped between -30 and +30 degrees).

Dynamic Visualization: Dropped weights are visualized as colored balls, with their size corresponding to their mass (ranging from 1-10).

Scoreboard:

Total Left Weight

Total Right Weight

Next Weight (randomly 1-10 kg)

Tilt Angle (in degrees)

Drop Log: A running log lists every weight drop, including its mass, side, and distance from the center. The most recent drop appears at the top.

Persistent State: The simulation's current state (all dropped objects) is saved in the browser's localStorage, allowing it to persist even after a page reload.

Reset: A "Reset" button completely clears the simulation (the plank, the log, and localStorage) to start over.

🚀 How to Use
Open the index.html file in a web browser.

Observe the "Next Weight" value on the scoreboard.

Click anywhere on the brown plank to drop that weight at that location.

Watch the plank tilt and see the scoreboard and drop log update.

Click the "Reset" button to clear the simulation.
