# Flex-Order-Manipulation
Practice project - manipulate order of cards using Flex Order

# Task
Modify the Frontend Mentor Challenge "3-Column Card" so that clicking on a card: 

*Required*
1. Moves it to the center
2. Reorders the other two card appropriately
3. Enlarges the center card
4. Returns any previously enlarged card to the standard size
3. Makes the enlarged card's edges appear over the cards behind it.

*If Manageable*
1. Animate movement for smooth transitions
2. Learn about using vars and import


# Secondary Goals
1. Properly comment HTML and CSS

# Tools
HTML
CSS

# Personal Development Goals
1. Develop more professional approach to tasks by:
    - Planning and documenting task in advance
    - Documenting and maintaining task list along the way

# Current Knowledge Status
1. Relatively comfortable with basic Flexbox & Grid use
2. Relatively comfortable with basic Semantic Markup

# Learned Along the Way
- It's not possible to create a click event using CSS only. There is a hack using a checkbox but I didn't pursue it far.
- "gap" on flexboxes
- transform: scale(), vars(),
- That my solution to the original Frontend Mentor challenge was overly complicated regarding sizing the individual flex items and aligning content in the grids. Should have simply used e.g. "flex: 1" and "grid-template-rows: 3rem auto 3rem;"
- using content structuring in html and pseudo class selectors to manipulate multiple classes simultaneously. And that "nested classes" may come to CSS in the future.
- General approach ideas to using rem and em, such as setting a base font pixel size in HTML, then setting a rem for a section, then using em inside that section. Haven't applied it here, but will try the approach in the next project.


# Task List
1. Create test page for becoming familiar with using 
    - flex order
    - transform
    - z index
2. Implement on project page
3. Check & improve Semantic markup
4. Check and improve HTML and CSS commenting 
5. Learn about vars for font size, colors etc.
6. Implement on project page
7. Learn and text transition animations on test page
8. Apply to project page


# Post Mortem
Was interesting to investigate what is possible, but generally not a very practical effect, as hovering over the cards is a little unwieldy and the effect offers no value. Plus, if you want to click a button, the cards moves. Would probably solve this by moving the buttons out of the grids, but it's not worth the effort here.

But I am happy that I achieved all my goals and had fun learning along the way! :)