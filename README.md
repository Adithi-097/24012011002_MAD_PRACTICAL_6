# Android Frame-by-Frame & Twin Animation

## Aim

Create an Android application to demonstrate Frame-by-Frame Animation and Splash Screen with Twin Animation.

## Description

This practical demonstrates different types of animations available in Android. The application contains a splash screen with a gradient background and twin animations, followed by a main screen containing frame-by-frame animations.

## Features

- Splash Screen Animation
- Frame-by-Frame Animation
- Twin Animation
- Scale Animation
- Translate Animation
- Rotate Animation
- Alpha Animation
- Animation Start Offset
- Animation Duration
- Radial Gradient Background
- Edge-to-Edge Content Display
- Animated Alarm Image
- Animated Heart Icon
- Navigation from SplashActivity to MainActivity

## Frame-by-Frame Animation

Frame-by-frame animation displays a sequence of images one after another to create the effect of movement.

In this application:

- The alarm image is animated using multiple frames.
- The heart icon is animated using multiple frames.
- `AnimationDrawable` is used to control the frame animation.

## Twin Animation

Twin animation applies different transformations to a view over a period of time.

The splash screen demonstrates the following animations:

- **Translate** - Moves the view from one position to another.
- **Rotate** - Rotates the view.
- **Scale** - Increases or decreases the size of the view.
- **Alpha** - Changes the transparency of the view.

These animations are combined using an animation set.

## Splash Screen

The application starts with a `SplashActivity`.

The splash screen contains:

- Gradient background
- UVPCE logo
- Frame-by-frame logo animation
- Twin animation
- Automatic navigation to `MainActivity`

The splash background uses a radial gradient with:

- Shape: Rectangle
- Center X: 0.9
- Center Y: 0.9
- Gradient Radius: 1500
- Start Color: Pink
- End Color: Blue

## Main Activity

The main screen contains:

- Alarm image
- "Create Alarm Time" title
- Description text
- Animated heart icon
- Create Alarm button
- Cancel Alarm button

The alarm image and heart icon use frame-by-frame animation.

## Android Components Used

- ImageView
- TextView
- Button
- ConstraintLayout
- MaterialCardView
- AnimationDrawable
- AnimationUtils
- Animation.AnimationListener
- SplashActivity
- MainActivity

## Android Concepts Studied

- Frame-by-Frame Animation
- Twin Animation
- AnimationDrawable
- onWindowFocusChanged()
- AnimationUtils
- loadAnimation()
- setAnimationListener()
- overridePendingTransition()
- finish()
- animation-list
- oneShot
- set
- startOffset
- duration
- scale
- translate
- rotate
- alpha
- Edge-to-Edge Display
- Splash Screen
- Gradient Drawable
- Converting SVG files into XML drawable resources

## Resources Used

The project contains animation resources in the appropriate `res` folders, including:

- Frame animation lists
- Twin animation XML
- Gradient drawable
- Animation frames
- Logo resources
- Heart animation frames
- Alarm animation frames

## Working

1. The application starts with the Splash Screen.
2. The UVPCE logo frame-by-frame animation starts.
3. Twin animations are applied to the logo.
4. After the splash animation finishes, the application opens `MainActivity`.
5. The alarm image starts its frame-by-frame animation.
6. The heart icon starts its frame-by-frame animation.
7. The user can interact with the Create Alarm and Cancel Alarm buttons.

## Conclusion

This practical demonstrates how Android applications can use Frame-by-Frame Animation, Twin Animation, Splash Screens, Gradient Drawables, and Edge-to-Edge UI to create an interactive and visually animated application.

