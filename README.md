# Team Profile Generator Summary:

https://edatez.github.io/TeamProfile_Generator/

A software engineering team generator command line application; a Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person. You can find the unit tests that all parts of code pass.

The application prompts the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. When the user completes building the team, the application creates an HTML file that displays a nicely formatted team roster based on the information provided by the user. 

# User Story:
```
As a manager
I want to generate a webpage that displays my team's basic info
so that I have quick access to emails and GitHub profiles
```
# Instructions for the Application:

![Screenshot 1](./Assets/10-OOP-homework-demo-1.png)
![Screenshot 2](./Assets/10-OOP-homework-demo-2.png)

In the `Develop` folder, there is a `package.json`, so make sure to `npm install`.

The dependencies are, [jest](https://jestjs.io/) for running the provided tests, and [inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user.

🎗 Remember, you can run the tests at any time with `npm run test`

# Directory structure:

```
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application
```

