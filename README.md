# HacktheNorth
Inspiration

As avid gym enthusiasts, the recent COVID-19 lockdowns have taken a significant toll on our fitness regimens. As a means to stay active, we tried building home gyms and incorporating workouts that can be done at home. The problem that remained was the lack of gym partners or trainers that could check our form to ensure we were doing exercises correctly and safely.

What it does

Form AI uses pose detection to determine if you are using proper form while exercising. For example, it can determine if your squat form is correct or not, just by turning on your camera!

How we built it

Form AI was built using Android, Java, and Google's ML pose detection library. To determine the correct form, 33 nodes were created representing the human form, with angles between different nodes detected and calculated by the pose detection library. We chose to build an Android app with the logic written in Java as most people use their phones while they are working out, and are easy to position to capture their workouts.

Challenges we ran into

For many of the members on our team, it was their first time developing an app with Android. So a lot of time was spent learning the basics of Android Studio and trying to build a functional UI and understand Android protocols.

Accomplishments that we're proud of

Having very little prior experience with Android, we are very happy with how our team performed and our app turned out. Additionally it was a challenge to use the pose detection library as we spent countless hours trying to get it to work and determining how it would check if the form is correct or not.

What's next for Form AI

Form AI would like to take our app to the next level by incorporating algorithms for a wider variety of exercises, and increased accuracy for advanced form checks, and creating a database to allow users to store workouts on the app. Form AI could also be expanded on by allowing users to upload videos to the app of an exercise and have it analyze the form of the video.
