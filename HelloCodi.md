# HelloCodi: tap the bee, hear the bee!

## Description of Lesson:
    - It's time to make your first app!
    - We are going to be making an app that has a picture of Codi the bee on it that will make a buzzing sound when you click on him.

## Getting Started:
- Your going to need a picture of Codi the bee and a mp3 sound file of his buzzing noise
- To download these items, you should click on the blue high lighted link, right click it and press "Save As" to your desktop so you can find them later.

### What are Components? 
- All of the components you will need can be found on the left side of the Designer Window. Think of these components as ingredients you need to make a recipe. Here are some components that will be helpful to know!
- Label- This will show you a text box on the screen you can use to type out words
- Button- This can be used as a "go" button to start your app
- Canvas- This can hold any pictures or animations you may need
- Accelerometer- Think of this component as a Wii Remote sensor that knows when you move or shake your phone in order to play videos or show messages 

### How to use components:
- To use a component for your ap, you need to click and drag it into the middle of the designer box. To double check that you did this right...when you add a component into the designer box you should also be able to see it in components list on the right side of the Viewer tab!

### Selecting Components and Setting Properties- It's time to build your app :D
- Step 1. Drag and drop the "Button" component from the User Interface list into the Viewer in the center of your screen
- Step 2. Now we need to get Codi the Bee! Under "Properties" and "Images" click on the text "None..." and click "Upload File." Next, click browse and find Codi the Bee on your desktop or where you saved it earlier!
- Step 3. Click on your codi.jpg file with Codi's picture, then click "Open" and finally click "OK"
- Step 4. We want to write "Touch the Bee" right underneath Codi. In order to do this, first delete "Text for Button1" in the Button's text property. 
- Step 5. From the User Interface Palette drag and drop the "Label" component and put it right below the picture of Codi. In the properties section on the right side, Change the text box to say "Touch the Bee". Next change the font size to 30. The words should look bigger now! Lastly,change the background color and text color to your favorite colors.
- Step 6. It's time to add the buzzing sound to the app. Under Palette, click "Media" and drag out the "Sound" component and put it in the Viewer just like you did with the Codi's picture. In the "Media" panel click "Upload File" and  add the Bee-Sound.mp3 sound that you saved earlier! Lastly, under the "Properties" panel click the word None and change Sound1's component to Bee-Sound.mp3. 

#### Activity Option**
- This activity is meant to try to help you understand the difference between event handler blocks and command blocks
- An event handler block (yellow) is used to specify WHEN the app needs to act a certain way. Do you want the action done when you click on a button? Or when you shake your phone? Or after 1 minute has passed? These are all things that the event handler block can take control of. 
- A command block (purple) is used to specify WHAT or HOW the app needs to act when an action is done. In this Codi app, the command is to make a buzzing noise.
- Now it's time to see if you can tell the difference... :) 

        **It's time for a quick game of Simon Says** 

Talk about which parts of the games were commands and which were event handlers! *Hint Remember you can only do something WHEN Simon says its ok*

#### Programming with Blocks 
- So far you've been making your app with the components in the "Designer"... but now we need to start changing the way our app actually works so we will need to use Block Editors. Think of Block Editors as lego pieces that you need to connect in a certain order in order to create a building the way you want it to look. For this app, we need the blocks to play the buzzing noise when you click Codi. 
- Step 1. In the Blocks Editor, you can find all the buttons you may need under the Button1 tab. The yellow blocks are called event handlers" and decide how the app should respond in different situations. For example, it'd be pretty cool to make a button that delivered you a slice of pizza every time you said "Pizza please!" 
- Step 2. Click on the Sound1 drawer and drag and drop Sound1. Connect the purple "call Sound1" play button to the yellow "when Button1 click do" block. These buttons should fit together like puzzle pieces and make a click sound when they connect. The purple buttons are called Command blocks which are the actions that are done when they are inside a yellow button.
Step 3. Test your work! When you click the button, you should hear Codi buzz. CONGRATS YOU MADE YOUR FIRST APP!!! 

### Time to save all your hard work!
- To save your work, you need to "package" your app to create an application package  that you can find later to use your app. 
- To do this... first click the "Build" tab at the top of your screen. Click build app (save to my computer) and save it some place safe that you can remember later ;) 
- Right now, we just have one screen. This means our app has one page, and that's it!