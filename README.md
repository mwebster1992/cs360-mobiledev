#cs-360-mobiledev

The app that I designed was meant to be a lightweight, simple weight logging app that allowed users to log and view their progress in a ListView.  To that end, I pared down the UI quite a bit for the final version.  Their is a login screen, and a home page that shows weights and allows basic CRUD functionality.  It is meant to be a quick way to track your weight.  The process of coding was arduous.  I began by implementing database functionality, using Logcat to print what was going in and out to ensure accuracy.  After that, I shifted toweard building the onClickListeners and all the alert dialogs.  Finally, I implement a permission structure to ask the user for permission to use SMS.
Testing was done using Logcat and the emulator running API 29 on a Google Pixel 2.  I chose this device because it is about four years old, the average age of smartphones in use, and supports all the way up to the newest version of Android.  Whenever I encountered an error, I was able to go look at Logcat and see what was going wrong.  Was the app not making it to a certain section of code?  Did a semicolon go awry?  I spent almost two hours trying to figure out one bug in the listview until I realized I had written ">" instead of ">=".  Coding is a masochistic action sometimes!
I had to innovate quite a bit--reading documentation, learning a ton of new Java lingo and Android functions.  It was the deepest dive into code I've done in several months, and definitely got me interested again after a stagnant period.  One of the coolest things I learned that I go to use was inflating layouts in my alert dialogs.  It was very satisfying to design the UI, build the alert dialog builder in code, and then have it show up when clicking buttons.  
