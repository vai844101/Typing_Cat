**Typing Cat**
Typing Cat is a React-based typing speed tester application that helps users improve their typing skills by providing a platform to practice typing and track their progress over time.

**Features**
Typing speed test with words per minute (WPM) and accuracy calculation
Real-time typing area with text display
Timer to track the duration of the typing test
Display of typing statistics after test submission
Responsive design with a user-friendly interface
Integration with Flowbite React components for UI elements.

**Project Structure**
.eslintrc.cjs
.gitignore
index.html
package.json
postcss.config.js
public/
src/
    App.css
    App.jsx
    assets/
        hero1.avif
        hero2.avif
        hero3.avif
    components/
        DefaultFooter.jsx
        GetStartedBanner.jsx
        Header.jsx
        Hero.jsx
        WorkingTimeline.jsx
    index.css
    main.jsx
    pages/
        home/
            Home.jsx
        typer/
            SpeedStats.jsx
            TextDisplay.jsx
            Timer.jsx
            TypingApp.jsx
            TypingArea.jsx
    redux/
        features/
            typingTestSlice.js
        store.js
    utils/
        randomText.js
tailwind.config.js
vite.config.js

**Installation**
Clone the repository:
git clone https://github.com/your-username/Typing_Cat.git
cd Typing_Cat
Install the dependencies:
npm install
Start the development server:
npm run dev
Open your browser and navigate to http://localhost:5173 to see the application in action.

**Usage**
Navigate to the home page to see the hero carousel and get started banner.
Click on "Get started" to begin the typing speed test.
Type the displayed text in the typing area within the given time.
Submit the test to see your typing speed (WPM) and accuracy.
Reset the test to start over with a new text snippet.

**Acknowledgements**
React
Flowbite React
Redux Toolkit
Tailwind CSS
Vite
