# SplashScreenApi
A simple to test Splash Screen API by google in android 12

Splash screens
bookmark_border
Android 12 adds the SplashScreen API, which enables a new app launch animation for all apps. This includes an into-app motion at launch, a splash screen showing your app icon, and a transition to your app itself.

Example of a splash screen
Figure 1: Example of a splash screen
The new experience brings standard design elements to every app launch, but it’s also customizable so your app can maintain its unique branding.

How the splash screen works
When a user launches an app while the app's process is not running (a cold start) or the Activity has not been created (a warm start), the following events occur. (The splash screen is never shown during a hot start.)

The system shows the splash screen using themes and any animations that you've defined.

When the app is ready, the splash screen is dismissed and the app is displayed.
