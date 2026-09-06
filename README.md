# Balloon Blaster 🎈🔫

Hey! This is a fun little browser game I made using JavaScript, HTML5 Canvas, and MediaPipe (TensorFlow.js). Basically, you play it using your webcam—you point your finger at the screen like a laser sight, and pinch your thumb and index finger together to shoot falling balloons. 

I wanted it to feel like an old-school arcade game but in AR, so everything is drawn in a blocky, Minecraft/80s pixel-art style. 

## What it actually does
* **Hand Gesture Controls:** Uses your webcam to track your hand. Your index finger aims, and pinching shoots. 
* **Mouse Fallback:** If your camera is glitchy (or you just want to test it quickly), you can use the mouse. The game has a built-in delay so the camera and mouse don't fight for control.
* **Speedometer UI:** Added a Slow, Medium, and Hard toggle because the default speed was making me lose my mind. 
* **Pure Code Art:** There are zero image files in this project. All the pixel art and explosion particles are drawn directly on the canvas using math and arrays.
* **Mobile Friendly:** The UI and camera window scale down properly if you try to open it on a phone.

## How to play
1. You get a 6-bullet magazine. Once you run out, you have to wait 3 seconds to reload.
2. You start with 5 lives. If a balloon crosses the bottom of the screen, you lose a life.
3. Pinch to shoot, don't miss!

## How to run it locally
Because browsers have strict security rules for webcams, you can't just double-click the `index.html` file to play it. 
1. Clone the repo.
2. Open it in VS Code (or whatever editor you use).
3. Start a local server (I just use the **Live Server** extension in VS Code).
4. Allow camera permissions when the browser asks, and you're good to go.
