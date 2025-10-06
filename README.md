# 🧩🧩🧩 Welcome to [Lucy's Sudoku](https://xxchen914.github.io/login/)!
Video Walkthrough: [YouTube Demo](https://youtu.be/at6aa8yGySE)  
## 💭 Write-Up
- **What was the most challenging piece of this assignment?Did you find it easy or challenging to work with HTML and CSS?  How long did this overall assignment take you?**  
Creating the game web using only HTML and CSS, without JavaScript or other development tools. Making the Sudoku grid adapt perfectly to different screen sizes required extensive use of media queries, and flexible units.   
CSS fine-tuning is very time-consuming, demandeding meticulous adjustments. Small changes in padding, margins, or grid sizing could break the entire layout.  
Limited interactivity: Without JavaScript, I couldn't implement actual game functionality like number validation, timer logic, or win conditions, which felt restrictive.  
About 10 hours. 
- **What decisions did you make when you made your site mobile friendly?**  
I prioritized readability and usability. I used CSS media queries to detect smaller screen sizes and adjusted the grid cell sizes, font sizes, and padding to prevent horizontal scrolling. On mobile, I considered moving the navigation bar to the bottom for better thumb accessibility, ensuring it didn’t block the game content. I also used flexible units (%, rem, and auto) instead of fixed pixels where possible, so elements would scale naturally on different screen sizes 
- **What did you take into account when you developed the design of your website? Is there anything that you’re particularly proud of?**  
For the design, I wanted a clean, modern, cute, and approachable feel. I used a light color palette with pink accents to create a friendly atmosphere while maintaining readability. I also ensured consistent spacing and typography using flexbox and grid for alignment and layout control.
I’m particularly proud of the Sudoku grid design and the fixed navbar that adapts nicely between desktop and mobile views. The layout feels intuitive, and each page maintains a consistent structure, which improves the overall user experience. The 9×9 and 6×6 Sudoku boards were fully styled with accessible input fields and clear subgrid borders, even without JavaScript.
- **Given more time or resources, what additional features would you add to your site in the future?**  
I would implement game logic using JavaScript — such as validating user input, generating random Sudoku puzzles, and tracking completion times. I would also add animations for button interactions and transitions between pages to make the experience smoother. Another feature I’d like to include is a scoreboard that dynamically updates and stores user data using local storage or a backend database. Finally, I’d like to enhance accessibility by including keyboard navigation and ARIA labels for screen readers.
- **How many hours did you spend on this assignment**  
I spent about 10 hours on this assignment, including designing the layout, writing CSS, and refining each page for consistency and mobile compatibility.
- **If you made any assumptions about this assignment, what are they?**    
I assumed that each page only needed to be static and linked via the navbar, without requiring functional interactivity. I also assumed the fake data (like usernames and scores) could be hardcoded
