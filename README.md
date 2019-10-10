# CPE 1040 - Introduction to Computer Engeneering

## Assignment: Creating a soil sensor extension for MakeCode for the micro:bit

### 1. Summary

This is not an assignment yet. It is a chance for you to tinker on your own with what will be assigned for next week. You have been provided with a pink anti-static bag containing:
  1. A small breadboard.
  2. A breadboard to micro:bit connector, already connected to the breadboard.
  3. A SparkFun soil sensor with three wires.
  
![alt text](https://github.com/ivogeorg/starter-preliminary-soil-sensor-extension/blob/master/images/soil-sensor-baggy.jpg "Soil sensor and accessories")

Follow the step-by-step [instructions](https://learn.sparkfun.com/tutorials/how-to-create-a-makecode-package-for-microbit/all) to create an extension for MakeCode that will allow you to use the soil sensor data in a micro:bit program. The extension will be added to MakeCode as an external package through the _Extensions_ tab.

### 2. (IMPORTANT) Soil sensor care

1. Do not power continously, only when you want to take a measurement.
2. Do not get the whole sensor wet.
3. Do not dip the rods directly into water.
4. If you don't have a pot of soil, use a cup of moistened cotton.

## Resources

### SparkFun soil sensor

1. Sensor hookup [guide](https://learn.sparkfun.com/tutorials/soil-moisture-sensor-hookup-guide). Although this provides an example using Arduino, there is a lot of good information for the sensor.

2. Electrical [schematic](https://cdn.sparkfun.com/datasheets/Sensors/Biometric/SparkFun_Soil_Moisture_Sensor.pdf), showing how the sensor is really a transistor with the two probes regulating the conductivity of the base.

3. Instructions for creating the extension [package](https://learn.sparkfun.com/tutorials/how-to-create-a-makecode-package-for-microbit/all).

4. SparkFun [product](https://www.sparkfun.com/products/13322) listing and documentation.

### micro:bit 

1. [micro:bit lessons](https://makecode.microbit.org/lessons).

2. [micro:bit ideas](https://microbit.org/ideas/).

3. A list of some more [advanced projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects).

4. The [projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects) at the [awesome micro:bit list](https://github.com/carlosperate/awesome-microbit).

### Github

1. Github Tutorial for Beginners ([webpage](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)).

2. Github Basics for Mac and Windows ([video](https://www.youtube.com/watch?v=0fKg7e37bQE)).

3. git & Github Crash Course for Beginners ([video](https://www.youtube.com/watch?v=SWYqp7iY_Tc)).

4. Introduction to Github for Beginners ([video](https://www.youtube.com/watch?v=fQLK8Ib_SKk)).

5. About `git` ([webpage](https://git-scm.com/about)).

6. `git` [documentation](https://git-scm.com/doc) (webpage, book, videos, reference manual).

7. [Github markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### JavaScript

1. Technically, the language which is used side-by-side with Blocks in the Makecode environment is a subset of [TypeScript](https://makecode.com/language), which itself is a superset of JavaScript (technically, [ECMAScript](https://www.ecma-international.org/ecma-262/10.0/index.html#Title)), with some JS features not implemented in Makecode.

2. The limited [JavaScript mini-tutorial](https://makecode.microbit.org/javascript) in Makecode. Make sure you read it but that can't be your only reference.

3. Official [TypeScript documentation]():
   1. TypeScript in 5 min [tutorial](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html). _**Highly recommended!** You will need to [download](https://www.typescriptlang.org/index.html#download-links) and install an integrated development envinronment (IDE). The two that I recommend are Visual Studio Code from Microsoft and WebStorm from JetBrains._
   2. The full documentation and reference is under _Handbook_. Bear in mind that you are drinking from the hose. Don't be surprised if not everything is presented in a strictly incremental manner.
   
4. In-browser TypeScript [playground](https://www.typescriptlang.org/play/index.html). Note that micro:bit specific code will not run, but you can still play. _Start making the distinction between a generic multi-purpose programming language (TypeScript) and functionality (packages, libraries, objects, etc.) that is specific to a particular device (micro:bit), though written in the same programming language._

5. A pretty good and very palatable JS tutorial with in-browser coding, by [Codecademy](https://www.codecademy.com/learn/introduction-to-javascript).

6. Extensive and detailed [JS tutorial](https://javascript.info/), with some advanced material thrown in. _**I like this one!**

7. The most authoritative JS resource on the Web, including tutorials and reference, by [Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript).
