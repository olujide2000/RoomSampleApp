# RoomSampleApp
The Room Sample App is a Java based android app . The Room Sample App takes in word and stores it in database and in this case we made use of Room Datase.
Some dependencies were imported in other to have full access to room database capabilities in android studio.
The launch page of the app is the mainactivity as shown below;
![Screenshot](https://user-images.githubusercontent.com/54988649/198890227-770a0e3a-43cf-4c24-add2-67986ecdf664.png)
Adding of word inputs into the database is done by clicking the floating button with a '+' sign as displayed on the image above.
The button navigates the user to the new activity page added through the manifest. The input page is displayed below;
![Screenshot](https://user-images.githubusercontent.com/54988649/198890427-ed597dab-e0bd-49ba-aa88-d70059bb432e.png)
The save button is used to save the input word(s) into the Room database as shown below;
![Screenshot](https://user-images.githubusercontent.com/54988649/198890546-031fe974-8416-434b-b0ca-6089a0157137.png)
The Room Sample App is a demostration of how to capture Live data and store in the database using the room database service as offered in Android studio.



Libraries Used
Room components
    implementation "androidx.room:room-runtime:$rootProject.roomVersion"
    annotationProcessor "androidx.room:room-compiler:$rootProject.roomVersion"
    androidTestImplementation "androidx.room:room-testing:$rootProject.roomVersion"

    // Lifecycle components
    implementation "androidx.lifecycle:lifecycle-viewmodel:$rootProject.lifecycleVersion"
    implementation "androidx.lifecycle:lifecycle-livedata:$rootProject.lifecycleVersion"
    implementation "androidx.lifecycle:lifecycle-common-java8:$rootProject.lifecycleVersion"

    // UI
    implementation "androidx.constraintlayout:constraintlayout:$rootProject.constraintLayoutVersion"
    implementation "com.google.android.material:material:$rootProject.materialVersion"

 
