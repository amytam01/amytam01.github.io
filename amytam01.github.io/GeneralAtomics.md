## General Atomics Aeronautical Systems
---

**Summer 2020**, I moved to San Diego to start my journey as a **software engineering intern** on the Army Modernization team at **GA-ASI**. 
<br>
Despite COVID-19, I was working on-site due to the sensitivity of the information I was handling. By the end of my internship, I had gained powerful skills in unit testing and C/C++ knowledge while using Jenkins, LINUX, and Vim. 
<br><br>
![At GA-ASI Offices](/images/GA.jpeg)
<br><br>
My role was specifically to test all functionality relating to three modules: Daylight Camera, Infrared Beacons, and Nose Camera. In short, unit testing confirmed the functionality of these modules, and allowed us to move the non-flight critical modules from the flight critical specific hardware to newly developed non-flight critical hardware. In addition, in the future unit tests would allow us to refactor legacy code if need be (as refactoring legacy code, especially in aerospace, can be time-consuming and costly). In total, I wrote **197 unit tests**.

---

### 1. Having written 197 unit tests, I learned the importance of writing clean code and good unit tests.
Before this internship, I had no sense of code style. However, having read tens of thousands of lines of code and having to interpret names and code to understand what specific modules did, I learned the importance of writing clean code to reduce code rot and to prevent future interns from the pain of having to guess what my code meant or did. I meticulously named all of my functions, and continuously built helper functions to make code more readable such that reading a function should make it immediately obvious what it did. I learned to make my unit tests modular, independent, and with specific names. For example, this is an example code I wrote for a unit test: 

```javascript
TEST(SomeFunction, VerifyFeatureWorks) {
  check(&msg); 
  verifyOff();
}
```
<br><br>
### 2. Unit testing, C/C++, Jenkins, LINUX, Vim, an how to write beautiful C
At the beginning of my internship, I was only versed in Python, HTML/CSS, and Java. Through this experience I was able to learn how to use tools like Jenkins, LINUX, and Vim. I went from barely knowing how to write "Hello World" in C, to being well versed in learning to write unit tests in C/C++. 

```javascript
if (learnGoodCodePractices){
  cout << "Less code rot! :)" << endl;
}
```
<br><br>
### 3. Even in times of crisis, people are resilient and come together.
I was incredibly lucky to have an in person experience with GA-ASI, surrounded by people who truly believe in their work. Through this experience I was able to find fulfillment in my days, and hope even as things seemed to get worse. 

I'd like to thank my mentors, Anthony Graca and JJ Krakowski for being there every step of the way.
