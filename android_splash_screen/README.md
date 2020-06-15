# Android Splash Screen

First Android app, seriously.

I have been working on web development for so long that I forgot that I used to do Java-based desktop applications before. As a novice Java developer, I thought that the easiest thing to implement on Desktop apps were splash screens. I was wrong.

Back in 2005, Java splash screens were a hack. The <code>[SplashScreen](https://docs.oracle.com/javase/6/docs/api/java/awt/SplashScreen.html)</code> class was noly introduced in Java 1.6. I had to compute first the bounds of the screen to center a floating panel (my splash screen), set the splash screen visible, and trigger a delay using <code>Thread.sleep</code>, before I can show the main window.

In this quick project, I decided to implement a native Android splash screen. You can see how easily you can setup your app to load a splash screen on startup.
