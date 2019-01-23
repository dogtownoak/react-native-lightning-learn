React-Native Lightning Learn:

React framework for mobile.  Allows you to run applications natively for Android and IOS.


React Native lets you build mobile apps using only JavaScript. It uses the same design as React, letting you compose a rich mobile UI using declarative components.

The apps you are building with React Native aren't mobile web apps because React Native uses the same fundamental UI building blocks as regular iOS and Android apps. Instead of using Swift, Kotlin or Java, you are putting those building blocks together using JavaScript and React.

React Native lets you build your app faster. Instead of recompiling, you can reload your app instantly. With Hot Reloading, you can even run new code while retaining your application state. Give it a try - it's a magical experience.

React Native combines smoothly with components written in Swift, Java, or Objective-C. It's simple to drop down to native code if you need to optimize a few aspects of your application. It's also easy to build part of your app in React Native, and part of your app using native code directly - that's how the Facebook app works.

Thousands of apps are using React Native, from established Fortune 500 companies to hot new startups. If you're curious to see what can be accomplished with React Native, check out these apps!

The simplest way to set the dimensions of a component is by adding a fixed width and heightto style. All dimensions in React Native are unitless, and represent density-independent pixels.

Setting dimensions this way is common for components that should always render at exactly the same size, regardless of screen dimensions.

Installed React-Native CLI tools

Steps to start:

React-native start (to run the server)

In new window:
React-native run-ios (should be able to run React-native run-android (but you need the emulator running first...which needs a Java SDK)



Expo is good but you can’t use an emulator with it.

Expo is the easiest way to start building a new React Native application. It allows you to start a project without installing or configuring any tools to build native code - no Xcode or Android Studio installation required (see Caveats).
Assuming that you have Node installed, you can use npm to install the Expo CLI command line utility:
npm install -g expo-cli


Then run the following commands to create a new React Native project called "AwesomeProject":
expo init AwesomeProject

cd AwesomeProject
npm start


This will start a development server for you.


An awesome style list that curates the best React Native libraries, tools, tutorials, articles and more:
http://www.awesome-react-native.com/

https://facebook.github.io/react-native/
