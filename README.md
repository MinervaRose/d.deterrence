# d.deterrence 
This space invader Android game app was created a few months after graduating from the Android Basics Nanodegree by Google, and a few days after watching the Dr Who New Year special episode Resolution. I'm a fan. 
This is a self-directed student project. 

## Overly dramatic trailer :collision:

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
* The [Canvas class](https://developer.android.com/reference/android/graphics/Canvas) holds the "draw" calls. To draw something, you need 4 basic components: a Bitmap to hold the pixels, a Canvas to host the draw calls (writing into the bitmap), a drawing primitive (e.g. Rect, Path, text, Bitmap), and a paint (to describe the colors and styles for the drawing)
* BitmapFactory class: using a BitmapFactory, you can create bitmaps in three common ways: from a resource, a file, or an InputStream. [Handling large images to avoid the OOM (out of memory) exception](http://www.informit.com/articles/article.aspx?p=2143148&seqNum=2). 
* [RectF](https://developer.android.com/reference/android/graphics/RectF) to represent graphic objects


## Description :milky_way: :crescent_moon:

A classic space invader android app game revamped. 
Includes several game states, life count, score management. 

## Design and illustration

* The pixel sprites were designed with the help of [this tutorial](https://design.tutsplus.com/tutorials/render-a-simple-3d-pixel-space-invaders-in-adobe-illustrator--cms-21185). For pixel-perfect artwork using Adobe Illustrator, check out [this tutorial](https://design.tutsplus.com/tutorials/how-to-create-pixel-perfect-artwork-using-adobe-illustrator--cms-23907). Avoid using anti-alias and gradients as advised [here](https://www.raywenderlich.com/2888-introduction-to-pixel-art-for-games). 

## Screenshot

<img src="https://user-images.githubusercontent.com/39020690/51057882-f1690900-15b4-11e9-86db-05c39af78e14.png" width="600">

## Further developments

Further development will include:
* Creating more levels
* Increasing the variety of villains
* Giving the user choice of gameplay music

## My feedback as an Android app development student :mortar_board:

Creating a game on your own is a great way to learn. When following a course, there can be too much hand-holding and not enough thinking. You can only solve problems if you actually encounter some! Using characters of one of my favorite shows increased my motivation. Customising a well-known game provided a good level of coding challenge.  


*Kind notice: as stated above this is a personal student project created by me, Sabrina Palis. I am neither providing the code, graphic assets, or distributing this project. Video trailer made whimsically with imovie, music by itunes, pixel artwork and fan art by me. This repo entry was done with the hope that provide inspiration for other coding students and future students* 
