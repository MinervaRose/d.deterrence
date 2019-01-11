# d.deterrence
This space invader Android game app was created a few months after graduating from the Android Basics Nanodegree by Google, and a few days after watching the Dr Who New Year special episode Resolution. I'm a fan. 
This is a self-directed student project. 

## Overly dramatic trailer

[![image alt text](https://user-images.githubusercontent.com/39020690/51015571-c2ae4c80-153a-11e9-84fa-e6963e44c0f6.png)](https://youtu.be/U7TU8Ob7hJA)

## Project overview

This first version of the project allowed me to work with android.graphics concepts:

* The [SurfaceView class](https://google-developer-training.github.io/android-developer-advanced-course-concepts/unit-5-advanced-graphics-and-views/lesson-11-canvas/11-2-c-the-surfaceview-class/11-2-c-the-surfaceview-class.html) to draw to the surface from a separate thread
* Creating a CustomView that extends SurfaceView and implements Runnable
* Initializing member variables and obtain reference to the SurfaceView's SurfaceHolder
* Locking the canvas
* Drawing on the canvas
* Unlocking the canvas
* Posting it to the surface
* Implementing pause() and resume() to start a new thread
* Handling user-touches and other data input that affects drawing
* The [Canvas class](https://developer.android.com/reference/android/graphics/Canvas) holds the "draw" calls. To draw something, you need 4 basic components: A Bitmap to hold the pixels, a Canvas to host the draw calls (writing into the bitmap), a drawing primitive (e.g. Rect, Path, text, Bitmap), and a paint (to describe the colors and styles for the drawing)
* BitmapFactory
* [RectF](https://developer.android.com/reference/android/graphics/RectF) to represent graphic objects


## Description 

A classic space invader android app game revamped. 
Includes several game states, life count, score management. 

## Further developments

Further development will include:
* create more levels
* increase the variety of villains
* give choice of gameplay music

*Kind notice: as stated above this is a personal student project. I am neither providing the code, graphic assets, or distributing this project. Video trailer made with imovie, music by itunes, pixel artwork and fan art by me. 
