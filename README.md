# Find-Friends-Android-App

**Screen 1 :**
Add new friend The first screen should allow the user to input details about their new friend such as their name, address, phone number and email. You must use the appropriate keyboard type for all inputs. Use appropriate layout and aesthetics for the views displayed on screen. Make sure text is legible on all views. You must check that the name, phone number and address of a friend cannot be empty. Also make sure that the phone number is 10-12 characters only. Show appropriate error message to the user if any of these validations fail. After providing all the valid data and clicking on a button, confirm the addition of new friend and the new friend’s info must be added to the list of friends. Use appropriate mechanism practiced in the class such as classes and arrays to maintain list of friends. Also display an options menu in the app bar that takes the user to the next screen to view list of friends and send the data along.

**Screen 2 :**
View friends list This screen should display all the friends’ information in a RecyclerView. Each item in the RecyclerView should display friend’s name, phone number, email and address as shown in the attached demo video. If email of a friends is empty use the default value of “not provided” to be displayed on RecyclerView item. Allow user to click on any item of RecyclerView and open next screen to view friend’s address and user’s location on map. 

**Screen 3 :** 
View location on map This screen will perform appropriate geocoding to obtain latitude and longitude for selected friend’s address. Using obtained lat and lng it will display location on map with friend’s name. This screen will also display user’s device location on map. Look at the given demo for appropriate labels for location annotations. Try to use locations that are nearby so that you can show multiple annotation in the frame.
