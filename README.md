# portfolio
This is a list of some of the projects I am working on or have worked on.

## Completed
These projects are finished! Hurray!

### [H-Appy](https://github.com/peter-james-allen/h-appy-client)
For the final project at Makers Academy, my group built a [dopamine-menu](https://www.youtube.com/watch?v=-6WCkTwW6xg) app. It consists of a cross-platform mobile app that allows users to input and modify menu items, and an API server to feed suggestions and save user info. The mobile app persists data to work as a stand-alone app. It can work offline, but the API server augmented the user experience.
This was our first time using React or React Native, and we completed the project within 11 days.

## Ongoing
These projects are a work in progress, but will be pretty cool when finished.

### [2048 Clone](https://github.com/jgumoes/2048)
I am working on a clone of the game 2048. I need a version that counts how many times the back button is pressed, and includes it in the high-score table. This will help counter my little brother's unfounded claims that I only achieve a high score by cheesing the back button. I also need a version that doesn't have ads. I'm writing the app in Typescript and React Native, and plan to use Mobx for state management.

### [Time-Based Event Service](https://github.com/jgumoes/time-based-event-service-specification)
This is a large and sprawling project to describe and implement a Bluetooth Low Energy service to initiate software events at specific times. A simple example is an LED lamp that works as an alarm clock, that can be programmed using a smartphone.

### [RTC Interface](https://github.com/jgumoes/RTC_interface)
A little platform-agnostic library to interface with I2C RTC chipsets (currently only supports DS3231). It is set up for unit testing on a PC through CMake and GTest, and will include a script for embedded testing with platformio. This library is intended as a dependency for my Device Time Service implementation, but is useful for other projects like clocks.
