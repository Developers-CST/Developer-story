# Developer-story
 This repository narrates the journey of setting up effective developer collaboration while implementing communication, tools, and project management strategies which was compiled and edited by R Keertish Kumar.

## Shift left testing
_Shift-left testing is an approach to software testing and system testing in which testing is performed earlier in the lifecycle (i.e. moved left on the project timeline). It is the first half of the maxim "test early and often"._

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/c19180b1-bccd-4d18-b6c8-ec0a5f610e99)

Our developement philosophy comes from this root.

## Choosing the IDE


### Visual Studio Code: A Great Choice for Coding

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/bc29a365-f5b1-4bd7-9614-1f93337deb16)


Visual Studio Code (VS Code) is an excellent platform for our coding adventures because of its lightweight nature and adaptability. It is an excellent text editor that effortlessly handles various programming languages without consuming, excessive computer resources. Its versatility is enabled through a vast collection of community-created extensions that act as add-ons, offering tailored tools and language support for one’s specific needs. Moreover, it seamlessly integrates with version control systems like Git, a vital aspect for collaborative projects

VS Code significantly eases coding for students. Its IntelliSense feature provides intelligent code suggestions, aiding in faster coding and navigation through complex code structures. Further support is available from a huge community, which is very helpful for troubleshooting or queries. Additionally, VS Code can integrate with other tools we might utilize for continuous integration (CI) and early-stage error detection ('shift-left' principle). Extra functionalities like security checks, code testing, or maintaining code cleanliness, there are extensions readily available. Overall, it's a flexible, user-friendly, and powerful tool perfectly suited to a student’s learning needs.

### Extensions for 'Shift-Left' Principles:

1. **Static Code Analysis Extensions:**
   - *ESLint for JavaScript/TypeScript projects:*
     - ESLint integrates into VS Code, aiding in early issue detection during development.
   - *Pylint for Python projects:*
     - Microsoft's official Python extension includes linting support via Pylint.

2. **Security Scanning:**
   - *Snyk for security scanning:*
     - Integrates with Snyk to identify and rectify security vulnerabilities in dependencies.

3. **Unit Testing:**
   - *Test Explorer UI:*
     - Provides a unified test explorer UI for various testing frameworks, enabling running unit tests within VS Code.

4. **Linting and Formatting:**
   - *Prettier for code formatting:*
     - A widely-used code formatter maintaining consistent code style.

5. **Continuous Integration (CI):**
   - *Azure Pipelines, GitHub Actions, or GitLab CI:*
     - Depending on version control and hosting platforms, CI pipelines can automate tasks like code analysis, testing, and deployment.

### Other Commonly Explored IDEs:

- **Eclipse:** Popular for Java development.
- **IntelliJ IDEA:** Known for strong support in Java and other JVM-based languages.
- **Atom:** Similar to VS Code, being lightweight and extensible.
- **PyCharm:** Specialized for Python development.

By Jaice Joseph and Hemal

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

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/e58bf29f-dd8f-4d5f-9cfc-7329a731bb8d)
![image](https://github.com/Developers-CST/Developer-story/assets/141417594/3cd31578-68f4-4e7a-b6f2-0f962b48c03a)


When I stumbled upon ESLint for JavaScript and pylint for Python, I found tools that completely transformed how I approached coding. They introduced me to something called "linting." Linting, powered by these tools, is like having a super attentive assistant that carefully goes through your code, examining every line for errors, style inconsistencies, and potential issues.

Imagine you're writing an essay, and there's a grammar checker ensuring your sentences are correct and making sure your writing style is consistent. Linting does a similar job but for code. It's not just about catching simple mistakes like forgetting a punctuation mark or using a variable that doesn't exist. It also checks if your code follows specific rules and styles that make it easier to read and understand.

By using ESLint and pylint right from the start, my code became cleaner and more organized. It was like having a code coach that guided me on the best practices of writing code. Plus, it helped me catch mistakes early in the game, similar to having a friend point out mistakes in your homework before submitting it, giving you a chance to fix them before they become big problems.

The cool thing about these tools is that they follow the "shift-left" principle. It's like being proactive—dealing with problems right at the beginning. Using ESLint and pylint meant I could detect and fix issues early, creating a solid code foundation. It's like building a sturdy house brick by brick, ensuring it can withstand any challenges that might come its way. Ultimately, linting became my go-to tool for not just finding errors but also for crafting top-notch, easy-to-maintain, and efficient code right from the get-go.

By Hemanth Sudarshan and Ankit Singh

## Exception handling

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/ea9438ef-aaeb-4618-9bf6-e67c20642093)


Writing custom exceptions in code is like crafting personalized error messages that provide clear insights into what went wrong. It's akin to creating signposts that guide developers to the root of an issue during the early stages of building software. By doing this, the development team can swiftly identify and rectify problems, similar to spotting and fixing mistakes in a draft before submitting the final version.

Imagine you're using a special tool in your code to fetch information from an external library or service. If, for some reason, that external tool isn't responding as expected, a custom exception can be designed to say something like "Hold on, the data is taking a break; try again later." This way, if there's a hiccup in getting the needed information, the system doesn't crash or confuse the developers with complex errors. It's like the code is politely letting you know that the external tool is on a short break and will be back to work soon, making it much simpler for both developers and users to understand and troubleshoot.his approach gracefully handles unresponsive situations, encouraging a retry mechanism and providing a more intuitive response, analogous to a system offering a friendly suggestion to revisit the operation at a more opportune time.

By Lavanya

## Actions Pushback

![image](https://github.com/Developers-CST/Developer-story/assets/141417594/1ef13767-85e3-45fc-ba10-48aa0451f50c)

Using pull requests (PRs) in GitHub helps developers share their code changes with the team and get feedback before adding those changes to the main code. It's like asking for advice on your work before making it official. This process allows others to check your code, suggest improvements, and make sure it works well with the rest of the project.

If your pull request fails, meaning the automated tests or checks find issues with your code, here's what you do: First, understand why it failed by checking the details of the problem. Fix the issues in your code and then run the tests again. Keep doing this until the tests pass and your changes work correctly. If you can't figure out how to fix the issues, create an issue in the repository to discuss the problem with your team. Additionally, notify the developer through email about the failure, so they're aware and can assist if needed. Once everything is good, your changes can be added to the main code for everyone to use after getting approval from the team.

By Ashraf

## Naming Conventions & Code Practices

![Common File Structures](https://github.com/Developers-CST/Developer-story/assets/141417594/2ba09dc1-6ace-487e-8d17-a7851f8fd3c0)

### Development port number

During web development, the default port number for displaying websites is 80 for HTTP and 443 for HTTPS. Port 80 was chosen for HTTP because it's the well-known port for unencrypted web traffic, while port 443 is the standard for encrypted HTTPS connections.Ports like 3000, 5000, and 8000 are commonly used. Port 5500 is also sometimes used, especially by tools like Live Server. However, the specific choice often comes down to personal preference, team conventions, and the availability of ports in your environment.

### Common File Structures

Following established nomenclature and file structure conventions fosters a common understanding among team members. This consistency promotes collaboration and effective communication by making it easier for team members to find and understand code and project structures.

#### Source Code

- **Folder Name:** `src` (source)
- **Explanation:** This folder holds the main source code of the project. It's where developers write the actual code for the application.

#### Public Assets

- **Folder Name:** `public`
- **Explanation:** This directory contains static assets that are publicly accessible, such as images, fonts, and HTML files visible to users.

#### Distribution Output

- **Folder Name:** `dist` (distribution)
- **Explanation:** The `dist` folder stores the output of the build process, including optimized and bundled code ready for deployment.

#### Libraries or External Modules

- **Folder Name:** `lib` (library)
- **Explanation:** External libraries or modules that are not installed via a package manager can be placed in this directory.

#### Tests

- **Folder Name:** `test` or `tests`
- **Explanation:** This directory holds test files and suites, ensuring the correctness of the code through automated testing.

#### Configuration

- **Folder Name:** `config`
- **Explanation:** Configuration files for various tools or settings used in the project are typically stored here.

#### Node Modules

- **Folder Name:** `node_modules`
- **Explanation:** This directory contains dependencies installed via a package manager, such as npm or Yarn.

#### Documentation

- **Folder Name:** `docs`
- **Explanation:** Documentation files for the project, providing information about the codebase and how to use the software.

#### Assets

- **Folder Name:** `assets`
- **Explanation:** Similar to the public directory, this folder is used for storing various project assets like images, fonts, and other media files.

#### Executable Scripts or Binaries

- **Folder Name:** `bin`
- **Explanation:** This directory contains executable scripts or binaries related to the project.

#### Stylesheets

- **Folder Name:** `styles` or `css`
- **Explanation:** Holds stylesheets, often in CSS or preprocessor formats (e.g., Sass or Less).


By Likith and Thanmay

### Developer experiences

So, I had been working on a new feature implementation in my project which used new modules. It worked well on my dev machine after merging the branches with the main, so I decided to create a pull request. Since we already had a Continuous Integration pipeline set up, I realized the pull request I set up failed the checks. When I read through the logs, I realized I hadn't updated the `requirements.txt` file which led to failure in checks at the build stage of the pipeline itself. If I hadn't had a pipeline and deployed it, it would have caused a major issue. So, having a good practice of making a pull request with a continuous integration pipeline made sure we deployed a site that worked on all machines.

When using the Snyk extension, I learned about open-source dependency vulnerabilities check where the `requirements` file with the modules is scanned with a database to check for vulnerabilities that could be exploited. Before using this tool, I used to have a basic check of the libraries that I used by looking through the [CISA Vulnerabilities summary](https://www.cisa.gov/news-events/bulletins/sb23-283) for security issues. Now, due to the extension, I can make sure a scan would keep the application secure.

By R Keertish Kumar

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




