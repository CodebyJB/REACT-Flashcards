# FlashCards React App

This is a simple React application that displays flashcards with questions and answers. Users can click on a flashcard to reveal the answer and click again to hide it.

## Demo

View project demo at https://jb-flashcards.netlify.app/

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies by running the following command:

   ```shell
   npm install
    npm start
   ```

## How It Works

The App component is the entry point of the application. It renders the FlashCards component, which is responsible for displaying the flashcards.

The flashcard data is stored in the questions array, where each question object has an id, question, and answer property.

The FlashCards component uses the useState hook to manage the state of the selected flashcard. When a flashcard is clicked, the handleClick function updates the selected flashcard ID in the state. The selected flashcard is highlighted by applying a CSS class.

The flashcards are rendered using the map function, which creates a <div> element for each question. Clicking on a flashcard toggles between displaying the question and the answer based on the selected ID.
