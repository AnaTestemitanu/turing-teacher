# Turing Teacher AI Assistant

Welcome to the Turing Teacher AI Assistant, a revolutionary tool revolutionizing the way we approach teaching preparation.


## Problem

Teaching has proven to be an overwhelming career, with almost 13% of newly qualified teachers leaving the profession within the first year of their qualification. This percentage increases to almost 19% leaving after their second year. The major reasons for this include an overwhelming workload, stress, and constant concern for creating high-quality class material.

## Solution

Our solution, the Turing Teacher AI Assistant, aims to reduce the workload on teachers by helping them with class preparation. Our application is designed to automate the class creation process based on the teacher's profile, class topic, reference books, and previous presentations. This assistance in class planning and preparation relieves the workload and stress on teachers.

## Technologies & Dependencies

This project leans on several key technologies and APIs.

- **Frontend**: The user interface is built using React.js for a smooth user experience.
- **Backend**: Node.js with Express.js serves as our robust backend framework.
- **AI System**: Our AI components are comprised of a custom Python-based AI Model, the Claude AI API, and DALL-E which together power our automations and predictions.
  - Please note that you will need to add your own API code for Claude AI and DALL-E in the following files:
    - [scripts/ClaudePrompts.py](./scripts/ClaudePrompts.py)
    - [src/api/class.api.js](./src/api/class.api.js)
    - [backend/app/src/controllers/presentation.controller.js](./backend/app/src/controllers/presentation.controller.js)
- **Database**: Sequelize.js provides a pleasant SQL construct for Node.js, and we use MySQL for our database needs.
- **Containerization**: Docker helps us keep our environments consistent and deployment seamless.

Make sure you have the proper keys and permissions necessary to use all aspects of this project. For security reasons, sensitive information like API keys and database credentials are not included in this repository.

## Getting Started

This project was bootstrapped with Create React App.

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser. The page will reload if you make any edits.
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

## Key Features

* **User Registration and Login** \- Register yourself with your details\, including your Name\, Age\, Years of Experience\, Gender\, Main Language\, and Slides that you like\.
* **Edit Profile** \- Customize and update the profile as per your requirement\.
* **Create a Class** \- Prepare the class content with ease using our auto class generator tool\. Just need to fill a form with details about your class like:
    * Name of the class,
    * Course Book PDF (optional) or Topic,
    * Level of the class,
    * Age of the class,
    * Tone of the study material (humor, with analogies),
    * Student group name, and
    * Indicate whether you are willing to share the presentation with others.
* **Previous Classes** \- Access and review all the classes created in the past\. Use easy filters to find a class by its name\, or by the student group\.
* **Explore & Share Resources** \- Discover presentations shared by other teachers\. A great way to gather different approaches and learn from peers\.

## Conclusion

We believe the Turing Teacher AI Assistant would serve as a great tool to uplift the present education system by reducing the burden on teachers which in turn can lead to an improvement in the quality of education imparted. Experience the Turing Teacher AI Assistant and let the magic happen!

We value your feedback. Feel free to contribute to our repository or report any issues you may face. We hope to make this application a great success with your support!