# self-driving-car-simulator
HTML and Canvas: We create a simple HTML document with a <canvas> element to draw the simulation. The canvas has an ID of simulationCanvas, which we will use to reference it in JavaScript. The canvas dimensions are set to 800x600 pixels.

Canvas and Context: Gets the canvas element and its 2D rendering context.
Car and Obstacle Arrays: Holds the cars and obstacles in the simulation.
Intervals: Variables to manage the intervals for adding cars and obstacles.
addCar Function: Adds a car at a random position, ensuring it doesn't intersect with existing cars.
addObstacle Function: Adds an obstacle at a random position.
stopAddingCars and stopAddingObstacles Functions: Stops the intervals for adding cars and obstacles.
animate Function: The main animation loop, clears the canvas, updates and draws each car and obstacle, and requests the next animation frame.
Execution
Interval Setup: Adds cars every second for 10 seconds and obstacles every 1.5 seconds for 5 seconds.
Animation Start: Calls the animate function to start the simulation.
This setup provides a basic simulation where cars avoid obstacles and each other, dynamically finding new paths. Further improvements could include more sophisticated pathfinding algorithms and more complex obstacle shapes and sizes.

