# Personality Quiz 

This project is a simple interactive personality quiz built using HTML, CSS, and JavaScript. Users answer fashion-based questions, and based on their choices, the quiz determines whether they are an introvert or an extrovert.

## 📁 Project Structure

.
├── index.html   # Main HTML file that displays the quiz
├── style.css    # CSS file for styling the quiz layout and design
├── script.js    # JavaScript file that handles quiz logic
└── assets/      # Folder containing all image files used in the quiz

## How It Works

1. The quiz asks three questions, each with two answer choices.
2. Each answer choice is linked to either introvert or extrovert behavior.
3. When a user clicks a button:
   - A score is updated.
   - The number of questions answered increases.
4. After all three questions are answered, the final result is displayed.

## Technologies Used

- HTML – structures the quiz content  
- CSS – styles the layout, images, and buttons  
- JavaScript – adds interactivity and determines the quiz result  

## File Breakdown

### index.html
- Displays quiz questions, images, and buttons
- Links the CSS and JavaScript files
- Shows the final result after the quiz is completed

### style.css
- Uses flexbox to align answer choices
- Styles text, images, and buttons

### script.js
- Tracks introvert and extrovert scores
- Uses event listeners to handle button clicks
- Displays the final personality result

## Quiz Logic

- Each answer increases either the introvertScore or extrovertScore
- After 3 questions:
  - Extrovert score ≥ 2 → "You are an extrovert!"
  - Introvert score ≥ 2 → "You are an introvert!"

## How to Run the Project

1. Download or clone the project files
2. Make sure all images are inside the assets folder
3. Open index.html in a web browser
4. Answer the questions to see your result
