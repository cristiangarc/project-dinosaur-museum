# Dinosaur Museum Project

The _Dinosaur Museum_ is opening! You've been tasked with building some challenging functionality for the automated systems recently installed at the museum.

To complete this project, you will need to write several difficult functions that will support attendees in finding out information about dinosaurs, finding the dinosaur's location, and calculating their entry fees.

This is the first major project of the course. Please read carefully through the instructions and rubric below.

## Project scoring

This project has five different parts on which you will be graded. Each part is weighted differently.

- 50% of the project is scored on **completion**.
- 20% of the project is scored through the **mastery rubric**.
- 10% of the project is scored through **stretch goals**.
- 20% of the project is scored through the **presentation rubric**.

In total, you must receive at least 70% to complete this project. For example, you could attain 40% of points through the completion requirements, 15% of points through the mastery rubric, 10% of points through the presentation rubric, and 5% of points through the stretch goals.

### Completion

Each function you complete within the three files located in the `src/` folder must be completed in full. If the function you write passes all of the tests, you will receive full credit. If your function passes some of the tests, you will receive partial credit.

#### Dinosaur facts

1. Complete the `getLongestDinosaur()` function.
1. Complete the `getDinosaurDescription()` function.
1. Complete the `getDinosaursAliveMya()` function.

#### Room details

4. Complete the `getRoomByDinosaurName()` function.
1. Complete the `getConnectedRoomNamesById()` function.

#### Ticket calculator

6. Complete the `calculateTicketPrice()` function.
1. Complete the `purchaseTickets()` function.

### Mastery rubric

This section of the project is designed to measure your increasing skill at writing good code and following best practices. To view components of the mastery rubric, view the appropriate assignment on Canvas.

### Stretch goals

This section of the project measures your ability to go above and beyond in creating your project. To score points in this section, you should incorporate a feature, technology, or skill not explicitly required by the project instructions.

When you submit your pull request, _make sure to include a description of any stretch goals you implemented._ You may choose from the list below or come up with features or tasks that are more relevant to your specific implementation of the project.

- Implement higher-order native array methods within your functions.
- Build helper functions that segment your code to make it more readable and understandable.
- Write new function(s) that answer a question about the data. For example, you could write a function that answers the question, "Which of the dinosaurs in this room were herbivores?"
- Create a solution video that walks through an implementation of your code, describing what is happening at each step.

Points will be allocated in this section at the discretion of the instructor.

### Presentation rubric

This section of the project is designed to measure your ability to present your project and your code. These skills are crucial for succeeding in the course and getting your first job as a software developer. To view components of the mastery rubric, view the appropriate assignment on Canvas.

## Project setup

Complete the steps below to get the project to run.

### Getting started

1. Fork and clone this repository.

1. Navigate to the cloned repository's directory on your command line. Then, run the following command:

   ```
   npm install
   ```

   This will install the libraries needed to run the tests.

1. Open up the repository in VSCode. Follow the instructions below to complete the Lab.

### Tests

To run the tests, you can run the following command from the command line. You will need to be in the root directory of your local directory.

```
npm test
```

### Test watcher

If you'd like, you can have the tests run constantly. This means that each time you save your file, your tests will be re-run. To do so, you can run the following:

```
npm run watch
```

Follow the on-screen prompts to exit out of the constant runner.

### Run test files individually

There are a lot of tests that are contained in this project. You can run a single test file individually by putting the name of the file after `npm test`. You can even only put part of the file name.

```
npm test facts
```

Keep in mind that the testing framework, Jest, will attempt to match as many files as possible. So, for example, the following command will run all of the tests because all of the tests are inside of the `dinosaur-museum-project/` folder.

```
npm test dinosaur
```

### Run tests individually

_After choosing a specific file to run,_ you can also specify which test you want to run. To do so, add `.only` after either `test` or `describe`.

```js
test.only("should return an array of everyone's name who is in the line, in order", () => {
```

This will either run the specific `test` or, in the case of adding `.only` to a `describe` block, all of the tests for a specific function.

> **NOTE:** Don't forget to remove this after you get the test to pass!

### Run file

If you want to manually test out your file, you can do so by running the following command.

```
node index.js
```

The output will be printed to your terminal.
