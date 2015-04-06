# Pig-Or-Pup-For-StackOverflow
When you open the game, you click "Go" in the tutorial, then an image appears. When one swipes this image, if it does not go to the game over screen, the image should fly off the screen. This action can be found on line 365 and line 446. A new image should then come in from the top or bottom. However, instead, the time bar at the top, as well as the background, are flying off screen, while that image is not. As you can see in the code, I tell "CurrentImage" to fly off screen and "NewImage" to drop in from the top, and I define those variables on lines 160-161. I also switch these variables on lines 382-400, within the function that moves the image.

My problem is that this image is not moving, as one can see by running the code in an IOS Simulator.
