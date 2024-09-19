# Web Dev Starter Code

## Overview
This project is a fake nature site about bears. It has been marked up to acomidates for accessibility issues and aims to make the site more "accessible" to different users. 

## Running 
- Open your terminal and cd into the directory you wish to clone the project into
- Use the Git Clone command to copy the repository: https://github.com/Megan-Aker/wildlife-website.git
- Once it is copied, cd into the repo
- Open the cloned repo in your IDE, then use live preview to view index.html to view the letter.

## Accessibility Lab Answers
1. The contrast ratio is 2.79:1 for the text color and background. The ideal ratio is around 4.5:1 for normal text and 3:1 for larger headings. Changing the text to be lighter on a dark background and vise versa makes for good contrast.

2. When tab is pressed a few times, it functions as expected jumping to the next element. However, it eventually jumps to the bottom of the page and then back to the related links.
To make the html more semantically correct, it should be wrapped in a <nav> element for better accessibility. The, font tag for the heading should be replaced with, h1 and h2 for better structure and screen reading. The css should reflect these changes to target these changes as well. 

3. The images need to have "alt" attributes for screen readers. 

4. The audio should include captions/transcript to make the audio more accessible using the tag p. There could also be a fall back link to download the audio file if the user's device can't open the audio file.

5. There should be a hidden visual label for screen readers using "sr-only" class. The comment form inputs need to be associated with their labels using the for attribute in the <label> tag.

6. To make the hidden comment keyboard accessible it needs to be a button not div. It can now be used with the enter key as well.

7. The table should have <th scope ="col"> for column headers and add caption tags for the table content. 

8. To make the overall website more accessible, the color scheme should be changed for better readability and an increased font size. For better keyboard navigation, there could be a skip to content link at the top of the nav bar so users can skip repetitive content. 

## Sources and Credits
- https://www.dreamhost.com/blog/make-your-website-accessible/ 
- https://github.com/shanep/web-dev-starter
- https://www.w3schools.com/html/html_accessibility.asp 

