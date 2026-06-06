# Globetrotter — Decisions Log

## Milestone 0: Setup and Planning
- Destination chosen: I chose this destination because I've always wanted to visit and I have an deep spiritual connection/resonance with the ancient architecteral wonders of this place.
- Primary audience: The audience is first time visitors because I think it would most intereest people who have never been to this place and makes my web page effective in creating a sense of curiosity and desire.
- One design decision that reflects the destination: I wanted the color thematics is to be rocky red because I thing it fits the theme of the geographical location itself.
- Wireframe format used (hand-drawn / Figma / other): The wireframe design focuses on simplicity, visual appeal and ease of navigation.

## Milestone 1: HTML Structure
- One HTML choice I made was inserting the nav tab in every page (home, attractions, food guide and gallery). This is because I wanted to lkeep the navigation bar visible from all pages.
- One thing Claude changed, that i had to correct was the "learn more" links in the guide page. I made them open the page on another tab by adding target="_blank" to the code.
- The page structure and te content structure (eg. weather to include a button and where)

## Milestone 2: CSS Styling
_Add entries after applying styles._
- I chose this font because I wanted to keep ot simple. I wanted the visual focus to be on the photographs.
- Claude suggested that the navigation bar be the width of the listed elements. Tab begins and ends where the listed item begins and ends. I changed this so that the bar stretches all the way from left to right with no margins. I did this because I think it is a better desiign choice and it is how I designed it on my wireframe.
- The image proportions didn't look right at first so I experinmented with the position and layout with the help of devtools on my live browser.


## Milestone 3: Flexbox Layout
_Add entries after implementing Flexbox._
- I deliberately made the flex direction column for the mobile version of the CSS.
- Claude amade the flex boxes on the gallery tab align to the center but I wanted them to allign at the fex start position (left most) so I had to set justify-content to be flex-start.
-I had to adjust my HTML by adding more classes. This was necessary because sI wanted to be more specific with my selectors.

## Milestone 4: Responsive Design
_Add entries after implementing media queries._
- I used the common breakpoints recommended on the course site because most devices screen sizes fit into those categories.
- The size and dimensions had to be different for almost all the images because the dimensions of an image for a desktop and a mobile is very different.
- There were no breakpoint suggestions from claude, I decided what it should be.
## Stretch Features
_Add entries if you implement any stretch features._
- I implemented three stretch features with minimal disruption to the core site. First, I added custom styling by integrating Google Fonts (Cinzel for headings and Inter for body text), plus subtle premium touches like letter spacing and refined button styling. Second, I added additional media by embedding an interactive map of Lalibela on the home page so users can quickly understand location context. Third, I added a travel newsletter sign-up form on the Food Guide page with name and email fields and a submit button (no backend), improving user engagement while keeping the project simple and stable.

