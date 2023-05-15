# WORD FREQUENCY COUNT APPLICATION

# NETLIFY LINK: https://sage-ganache-4a2bb9.netlify.app/


This is a Word Frequency Count application built using React.js. It fetches the contents of a text file, calculates the frequency of each word, and visualizes the top 20 most occurring words as a histogram. It also provides an option to export the histogram data as a CSV file.

FEATURES:

1. Fetch the contents of a text file
2. Calculate the frequency of occurrence of each word
3. Visualize the top 20 most occurring words as a histogram
4. Export the histogram data as a CSV file


PREREQUISITES:

To run this application locally, you need to have the following installed:
Node.js
npm (Node Package Manager)

INSTALLATION:
1. Clone the repository:
git clone https://github.com/your-username/word-frequency-count.git

2. Navigate to the project directory:
cd word-frequency-count

3. Install the dependencies:
npm install

4. Start the application:
npm start

5. Open the application in your browser:
http://localhost:3000

USAGE:

1. Upon loading the application, you will see a "Submit" button.

2. Click on the "Submit" button to fetch the contents of a text file. The application fetches the contents from the URL https://www.terriblytinytales.com/test.txt.

3. The application parses the text and calculates the frequency of occurrence of each word.

4. A histogram chart is generated, visualizing the top 20 words with the highest occurrence. The X-axis represents the words, and the Y-axis represents the number of times they occurred in the text.

T5. export the histogram data, click on the "Export" button. This will download a CSV file containing the word-frequency data.

COMPONENTS:
The application consists of the following main components:

1. APP: The main component that renders the Submit button, handles data fetching, word frequency calculation, and CSV export. It also renders the HistogramChart component.

2. HistogramChart: A reusable component that displays the histogram chart using the Recharts library.


LIBRARIES AND PLUGINS USED:
The Word Frequency Count application utilizes the following libraries and plugins:

1. React.js: A JavaScript library for building user interfaces.

2. axios: A popular library for making HTTP requests. It is used to fetch the contents of the text file.

3. recharts: A charting library for React.js that provides the components needed to visualize data as a histogram.

CONTRIBUTING:

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please create an issue or submit a pull request.


ACKNOWLEDGEMENTS:

1. This application was built using React.js, a powerful JavaScript library for building user interfaces.
2. Data fetching is handled using the axios library.
3. The histogram visualization is created using the recharts library.


Please feel free to customize this README file based on your specific project details, dependencies, and requirements. Provide clear instructions for installation, usage, and any other relevant information to help users understand and use your Word Frequency Count application.




# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
