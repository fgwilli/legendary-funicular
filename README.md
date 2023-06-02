Make sure you have a sound effect file named sound_effect in the res/raw directory of your Android project.

To use this code, you need to create a new Android project in Android Studio, create an XML layout file named activity_sound_effects.xml in the res/layout directory, and add a button with the ID play_button to the layout file.

This example uses the SoundPool class to create and play sound effects. It checks the device's API level to determine the appropriate way to create the SoundPool object. The sound effect is loaded from the resources and played when the button is clicked. The SoundPool resources are released when the activity is destroyed to free up system resources.

Remember to add the necessary permissions for audio playback in your Android manifest file:
