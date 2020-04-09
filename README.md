# camera_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


Install VSCode
Install Android Visual Studio
Setp up android emulator. (for android and pick whichever emulator you want).
Install xCode (comes with iphone emulator but you might have to set it up)
Download and set up the path for flutter.
Add flutter and dart extensions on vscode.
Clone git.
Ctrl + Shift + P (for mac its command + shift + p) and type in flutter and pick launch emulator
Pick emulator you would like to run. (I used Pixel 3 XL and iphone 11)
In VSCode terminal "flutter run" to start the app.
Run command "flutter doctor" to see what you are missing.

Potential Issues
If widgets not loaded
    * flutter packages get
    * flutter packages upgrade
If build fails.
    * flutter clean
If iPhone emulator build fails
    * xattr -cr [filepath to git directory on local laptop]
Make sure no device is plugged in because it will use that as the emulator
On Mac I had the problem of some files would create itself but only on the Mac.