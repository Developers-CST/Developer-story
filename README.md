# Developer-story
 This repository narrates the journey of setting up effective developer collaboration while implementing communication, tools, and project management strategies which was compiled and edited by R Keertish Kumar.

## Shift left testing
_Shift-left testing is an approach to software testing and system testing in which testing is performed earlier in the lifecycle (i.e. moved left on the project timeline). It is the first half of the maxim "test early and often"._

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/c19180b1-bccd-4d18-b6c8-ec0a5f610e99)

Our developement philosoply comes from this root.

## Choosing the IDE

Visual studio code

## Security tools

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/b23e71ec-50f7-494d-8d75-898df178550f)

I was working on my super cool computer projects, I met this amazing tool called Snyk. It was like having a superhero sidekick for my coding adventures. Snyk helped me find and fix problems in my code, making sure my creations were strong and safe.

But my curiosity led me to explore other coding buddies. SonarQube was like a wise mentor, always checking if my coding words were just right. Then there was OWASP Dependency-Check, the guardian who made sure no sneaky bugs tried to creep into my work.

As I continued my coding journey, I discovered the "shift-left" secret. It was like putting on a superhero cape early on, catching problems right from the start. Snyk and my new buddies were there, helping me build a fortress of code that could withstand any challenges.

By Manoj Kumar R and Pruthvi Reddy

## Unit testing tools

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/f4e34cff-0000-494e-81fd-9b2a32c67e93)
![image](https://github.com/Developers-CST/Developer-story/assets/141417594/6f1865c8-5815-4c9a-bd94-4ebe86b09044)



We used Jest as our tool for unit testing. Jest is a popular JavaScript testing framework maintained by Facebook. It is designed to be simple, fast, and developer-friendly. Jest is often used for testing applications, libraries, and scripts written in JavaScript.

Coming to the python testing we have used pytest as it has a very simple syntax for writing tests, fixtures for test setup and for debugging. It is also highly extensible through plugins for code coverage, fixtures and more.Finally it provides us details and informative reports after test runs, making it easy to identify which tests passed or failed and why.

We also explored Quixote that is a CSS testing framework developed by the team at the Financial Times. It is designed to facilitate automated testing of web applications by allowing developers to write tests that verify the visual appearance of their CSS styles. But we did not prefer it as it might lead to bloated code and much customizations are not possible with it and we should be very clear on what part of the famework must be used.

We have also included unit testing at the initial level for the following reasons:-
- Early Detection of Bugs
- Immediate Feedback

Using of Jest helped us in the shift left process by the following ways:-
- While using jest for java script it helped in the early detection of bugs by writing unit tests. It focusses on individual components, providing us a granular level of testing to identify problems.
- As Jest is often integrated with the CI/CD pipeline it helped us in automated testing 
- Jest also provides immediate feedback when a test fails.

By Pooja Manyam and Krutarth

## Lint tools

Pylint and Eslint

## Exception handling

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/ea9438ef-aaeb-4618-9bf6-e67c20642093)


Writing custom exceptions in code is like crafting personalized error messages that provide clear insights into what went wrong. It's akin to creating signposts that guide developers to the root of an issue during the early stages of building software. By doing this, the development team can swiftly identify and rectify problems, similar to spotting and fixing mistakes in a draft before submitting the final version.

Imagine you're using a special tool in your code to fetch information from an external library or service. If, for some reason, that external tool isn't responding as expected, a custom exception can be designed to say something like "Hold on, the data is taking a break; try again later." This way, if there's a hiccup in getting the needed information, the system doesn't crash or confuse the developers with complex errors. It's like the code is politely letting you know that the external tool is on a short break and will be back to work soon, making it much simpler for both developers and users to understand and troubleshoot.his approach gracefully handles unresponsive situations, encouraging a retry mechanism and providing a more intuitive response, analogous to a system offering a friendly suggestion to revisit the operation at a more opportune time.

By Lavanya

## Actions Pushback

Github build fail

## Naming Conventions & Code Practices

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/2ba09dc1-6ace-487e-8d17-a7851f8fd3c0)

Common File Structures: Following established nomenclature and file structure conventions fosters a common understanding among team members. This consistency promotes collaboration and effective communication by making it easier for team members to find and understand code and project structures.

During web development, the default port number for displaying websites is 80 for HTTP and 443 for HTTPS. Port 80 was chosen for HTTP because it's the well-known port for unencrypted web traffic, while port 443 is the standard for encrypted HTTPS connections.Ports like 3000, 5000, and 8000 are commonly used. Port 5500 is also sometimes used, especially by tools like Live Server. However, the specific choice often comes down to personal preference, team conventions, and the availability of ports in your environment.

Source Code:

Folder Name: src (source)
Explanation: This folder holds the main source code of the project. It's where developers write the actual code for the application.
Public Assets:

Folder Name: public
Explanation: This directory contains static assets that are publicly accessible, such as images, fonts, and HTML files visible to users.
Distribution Output:

Folder Name: dist (distribution)
Explanation: The dist folder stores the output of the build process, including optimized and bundled code ready for deployment.
Libraries or External Modules:

Folder Name: lib (library)
Explanation: External libraries or modules that are not installed via a package manager can be placed in this directory.
Tests:

Folder Name: test or tests
Explanation: This directory holds test files and suites, ensuring the correctness of the code through automated testing.
Configuration:

Folder Name: config
Explanation: Configuration files for various tools or settings used in the project are typically stored here.
Node Modules:

Folder Name: node_modules
Explanation: This directory contains dependencies installed via a package manager, such as npm or Yarn.
Documentation:

Folder Name: docs
Explanation: Documentation files for the project, providing information about the codebase and how to use the software.
Assets:

Folder Name: assets
Explanation: Similar to the public directory, this folder is used for storing various project assets like images, fonts, and other media files.
Executable Scripts or Binaries:

Folder Name: bin
Explanation: This directory contains executable scripts or binaries related to the project.
Stylesheets:

Folder Name: styles or css
Explanation: Holds stylesheets, often in CSS or preprocessor formats (e.g., Sass or Less).

By Likith and Thanmay

## Our proposed framework

### Collaboration Best Practices

### Communication

- Create a WhatsApp group for communication.
- Implement 2 min, 5 min, and 10 min pitches for development work presentations.
 
### Tools

- Use standard frameworks/tools with stated purposes in the Readme.md.
- Use a security tool like snyk.
- Use a unit testing tool like jest or pytest.
- Use a lint tool like eslint or pylint.

### Exception Handling

- Write custom exceptions for code errors within functions.
- Create exceptions for third-party APIs, print "Come back later" for unresponsive APIs.

### Actions Pushback

- Utilize pull requests to add code.
- If pull request actions fail, create an issue in the repo and email the developer.

### Naming Conventions & Code Practices

- Use consistent port numbers during project presentations.
- Follow established file structure practices, like "src" for source files.




