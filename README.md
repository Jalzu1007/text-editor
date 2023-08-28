# text-editor

## Description

This project is a browser-based text editor that meets the criteria of a Progressive Web Application (PWA). It utilizes data persistence techniques, including IndexedDB, to ensure content reliability even when offline. The app is designed to be intuitive and user-friendly, allowing developers to create and store notes or code snippets, with the ability to access them anytime, anywhere.

The motivation behind building this project was to showcase a practical application of the concepts learned throughout the course. By creating a robust text editor with offline functionality, this project highlights skills in web development, data persistence, and PWA implementation.

This project addresses the need for a reliable platform where developers can store their notes or code snippets, regardless of whether they have an active internet connection. By utilizing IndexedDB and adhering to PWA principles, the text editor offers seamless data retrieval and storage, enhancing productivity and workflow.

Through building this text editor, I gained a deeper understanding of data persistence mechanisms, such as IndexedDB, and how they can be integrated into a web application. Additionally, I learned about PWA concepts and the importance of optimizing web apps for offline use, leading to a more resilient and user-friendly experience.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory using the terminal.
3. Run `npm install` to install the required dependencies.
4. Run `npm run start` to start the backend and serve the client.
5. Run `npm run build` and `npm run start:dev` to run application.
6. Open your web browser and navigate to the provided local URL.

## Usage

1. Open the text editor application using your preferred web browser.
2. Upon opening, the application will automatically create an IndexedDB database storage.
3. Enter your desired content in the text editor.
4. Click outside the DOM window to trigger the automatic content saving to IndexedDB.
5. Even if you close the editor and reopen it, the content will be retrieved from IndexedDB, ensuring data persistence.
6. Click on the "Install" button to download the web application as an icon on your desktop.
7. The application employs a service worker created with workbox, enabling the caching of static assets for offline use.

To experience text-editor application, visit our deployed Heroku website: [JATE]()

## Credits

Third-Party Assets:

- [Workbox](https://developers.google.com/web/tools/workbox)
- [WebpackPwaManifest Plugin](https://www.npmjs.com/package/webpack-pwa-manifest)
- [idb Package](https://www.npmjs.com/package/idb)
- [The Full-Stack Blog - Heroku Deployment Guide](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide)

## License

N/A