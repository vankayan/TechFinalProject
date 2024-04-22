*<p align="center"> University of Cincinnati </p>*
*<p align="center"> Information Technology  </p>*
*<p align="center"> Tech for Mobile apps  </p> <br />*
**<a align="center" href="https://dbms2704.herokuapp.com/">
#FITNESS APP
</a>**

# Teammates
- Sainadha Reddy Penugonda - M15890050  
- Archana Vankayalapati- M15801476

# Table of Contents
- [General info](#desc)
- [Run](#run)
- [Technologies Used](#pre)

<a name="desc"></a>
# General info
FITNESS APP
- Clients approach
- Freelancers Approach

<a name="run"></a>
#How to run the code

## Then

Run The App

### npm start

Runs your app in development mode.

Open it in the [Expo app](https://expo.io) on your phone to view it. It will reload if you save edits to your files, and you will see build errors and logs in the terminal.

#### npm run ios

Like npm start / yarn start, but also attempts to open your app in the iOS Simulator if you're on a Mac and have it installed.

#### npm run android or npx expo start and then press a to run on android

Like npm start / yarn start, but also attempts to open your app on a connected Android device or emulator. Requires an installation of Android build tools (see [React Native docs](https://facebook.github.io/react-native/docs/getting-started.html) for detailed setup).


Open the Source code folder and open hire book code in your editor and
$ npm i
$ npm run expo ..
Open localhost: and to find the magic

This is the Home Page of the output

![HomePage](images/1.jpg)

When you click on the "Full Body Workouts" option, it will take you to the `FitScreen.js`, where you can engage with the exercises designed for the entire body.


![Fitscreen](images/2.jpg)



![Fitscreen](images/3.jpg)

![Fitscreen](images/4.jpg)

![JumpingJacks](images/5.jpg)

Upon clicking "start," the application will navigate to the `RestScreen.js`, where users can take a break and rest between workout sessions.

![RestScreen](images/6.jpg)

![FitScreen](images/7.jpg)

In the `context.js` file, there's code that keeps track of the calories burned, workouts completed, and minutes spent exercising. Once you finish a workout, this information updates automatically on the home page, so you can see your progress right away.

![Finishing the exercises](images/8.jpg)

![Fitscreen](images/9.jpg)

FitScreen is a React Native component for fitness apps, displaying exercise details and allowing users to track progress. It features seamless navigation, exercise completion tracking, and responsive design



![HomeSCreen](images/10.jpg)

HomeScreen is a React Native component for fitness apps, showing key stats and offering dark mode toggle. It's user-friendly and integrates seamlessly with fitness data.


![Restscreen](images/11.jpg)

RestScreen in React Native offers a countdown timer for users to take a break, seamlessly integrating with navigation. It provides visual cues and ensures a refreshing pause during workout sessions.


![Workoutscreen](images/12.jpg)


WorkoutScreen in React Native displays exercise details with completion status. It enables users to start their workout routines with a simple click.


![App](images/13.jpg)

This code defines an App component that wraps a FitnessContext provider around a StackNavigator component, also setting the status bar style and background color using Expo's StatusBar component.

![context](images/14.jpg)

This code creates a context named FitnessContext to manage fitness-related state data, including completed exercises, workout count, burned calories, and exercise duration. It utilizes React's createContext and useState hooks to initialize and update the context's state values.


![stacknavigator](images/15.jpg)

This code defines a StackNavigator component using React Navigation for native platforms, managing a stack of screens including Home, Workout, Fit, and Rest screens. It utilizes createNativeStackNavigator to create a stack navigator and sets options to hide the header for all screens.


Overview:
In a fitness app, the FitnessContext keeps track of important fitness details like completed workouts, calories burned, and workout duration. It acts as a central hub for storing and managing this information. The StackNavigator handles moving between different parts of the app, like the Home screen for an overview, Workout screen to start exercising, Fit screen to track progress, and Rest screen for recovery. Together, these components ensure users can smoothly navigate and keep tabs on their fitness journey, from starting a workout to resting afterward, all while keeping their data organized and accessible.


This fitness software seeks to offer users a comprehensive platform for tracking fitness progress, managing exercises, and monitoring health objectives. It has a variety of displays and features to ensure a smooth exercise experience.


The project begins by creating the FitnessContext, which serves as a consolidated repository for critical fitness data. React's createContext and useState are used to handle variables such as completed workouts, calories burnt, and exercise duration. This context serves as the backbone, allowing for simple access and modification of fitness-related information across the program.


Navigation: The program then implements scrolling using the StackNavigator. This component makes use of the React Navigation library's NavigationContainer and createNativeStackNavigator methods. It allows for seamless transitions between displays, including the Home screen for an overview, the Workout screen for workout routines, the Fit screen for progress monitoring, and the Rest screen for recuperation intervals.


Screening Components:
Each screen in the app serves a specific purpose:
Home Screen: Offers an overview of the app's features and options for navigation to different sections.
Workout Screen: Allows users to select and perform various workout routines, providing instructions and timing.
Fit Screen: Displays users' fitness progress, including metrics like calories burned, workout duration, and achievements.
Rest Screen: Provides a dedicated space for users to rest and recover between workouts, promoting a balanced fitness regimen.

UI Customization:
Throughout the project, UI aspects are carefully considered to ensure a visually appealing & user-friendly experience. Elements like as headers, navigation choices, & screen layouts are tailored to match the app's style and improve usability.

The project has amazing features such as establishing preferences, tracking your progress, and allowing you to interact with the app seamlessly. It's similar to having buttons to click, fields to put in, and bars that show how far you've progressed in your fitness quest. These features make it simple for you to use the app and track your progress toward your fitness and wellness objectives.


<a name="pre"></a>
# Technologies Used
React Native
JavaScript
React
Expo
React Native Navigation


Video Link: https://mailuc-my.sharepoint.com/:v:/g/personal/vankayan_mail_uc_edu/EdrZnEWKL-VKkC_jzvksFGABRfXR-S_65cNZIMCDpZumFg?e=NAqcWZ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D



<a name="pre"></a>
# CODE
Best to see in 67%