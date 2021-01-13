# Git-Flow-Practice

This project is designed for one to practice the Git/Github workflow here at Lambda School. You will be able to follow along with [this pre-class video](https://youtu.be/4fLr6ah82bE) and use this assignment to demonstrate your ability to work within this flow. Watch this video, then follow the instructions listed below to complete the assignment

## Directions to complete this assignment

- [ ] Create your own version of this repo - Fork
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add your name to the list of names below.
  - [ ] Run your usual git commands or adding/commiting and pushing **Be sure to push to your branch**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).





## ADD your name here

- Steve Rogers
- Ryan Hamblin
- Arthur Camara

1. What is Semantic HTML? 
    2. What is HTML used for? 
        Answer: HTML is used for structure on a webpage.
    3. What is an attribute and where do we put it? 
        Answer: An attribute provides information about an element. An attribute is inside the start tag and within quotation marks.
    4. What is the h1 tag used for? How many times should I use it on a page?
        Answer: The h1 tag is used as the title of a page or post and should only be used once per page.
    5. Name two tags that have required attributes
        Answer: The alt tag and the src tag both have required attributes.
    6. What do we put in the head of our HTML document? 
        Answer: We put the page title and the links to files like css inside the head.
    7. What is an id? 
        Answer: An id is a unigue attribute for an html element.
    8. What elements can I add an id to? 
        Answer: Elements that start with a letter can have an id.
    9. How many times can I use the same id on a page? 
        Answer: The same id can only be used once on a page.
    10. What is a class? 
        Answer: A class is an attribute that refers to one or more HTML elements.
    11. What elements can I add a class to? 
        Answer: The class attribute can be used on any HTML element.
    12. How many times can I use the same class on a page? 
        Answer: A class can be used multiple times on the same page.
    13. How do I get my link to open in a new tab?
        Answer: I set the target attribute to _blank (target="_blank"), in order to get my link to open in a new page.
    14. What is the alt attribute in the image tag used for? 
        Answer: The alt attribute is used to give an alternate text for an image. This is helpful if an image cannot load or if a user is relying on a screen reader and cannot see the images that are displayed. 
    15. How do I reference an id?
        Answer: To reference an id, I use the #directly before the name of the id, followed by {}, putting my desired commands inside the {}.
    16. What is the difference between a section and a div
        Answer: The section tag creates independent sections within a webpage that have logically connected content. The div tag is an empty container specifying a division or section.
    17. What is CSS used for? 
        Answer: CSS is the language used for describing the presentation of webpages, including colors, layout, and font.
    18. How to we select an element? Example - every h2 on the page
        Answer: In CSS, one would use the selector h2 {}, with the desired command appearing in the braces.
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
        Answer: Class would be used for multiple instances of an element, while id would be used only for a single occurance. If my menu page on a webpage was going to have three sections, but the first section was going to have unique hover animation and maybe even audio, then I would want to use an id on that first section to separate its CSS from that of the other two sections. Those other two sections could receive class selections for their shared CSS.
    20. How do we select classes in CSS?
        Answer: We select class using the period (.) followed by the specific class name, as it appears in quotations in the appropriate html.
    21. How do we select a p element with a single class of “human””?
        Answer: The starting p tag would look like <p class="human"> in the HTML, and would then be called up as .human {} in CSS.
    22. What is a parent child selector? When would this be useful? 
        Answer: A parent child selector is written using the greater than symbol ">" when that symbol is used between two other selectors. The selector to the left becomes the parent and the selector to the right becomes the child. This lets the developer choose the direct descendent of the parent element, making it possible to precisely target certain elements at certain points of the document.
    23. How do you select all links within a div with the class of sidebar?
        Answer: I would use the tag <div class="sidebar"> to select all the links within div with the class of sidebar.
    24. What is a pseudo selector?
        Answer: A pseudo selector is when the browser, in the background, decides that various elements belong together in a class, sometimes based on things that happen when a visitor visits a page.
    25. What do we use the change the spacing between lines?
        Answer: We can use the void element br to change the space between lines.
    26. What do we use to change the spacing between letters?
        Answer: We use the &nbsp to change space between text.
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
        Answer: We would use the CSS property text-transform with the value uppercase to change to all capital letters.  We would use the CSS property text-transform with the value lowercase to change to lowercase letters.  We would use the CSS property text-transform with the value capitalize to change the first letter of every word to capital letters.
    28. How do I add a 1px border around my div that is dotted and black?
        Answer: With appropriate line spacing, I would type div { border: 1px dotted #000000; }
    29. How do I select everything on the page? 
        Answer: The * selector selects all elements.
    30. How do I write a comment in CSS?
        Answer: I would beging my single line comment with */ and end it with /*. 
    31. How do I find out what file I am in, when I am using the command line? 
        Answer: I would type "pwd" while using the command line.
    32. Using the command line - how do I see a list of files/folders in my current folder?
        Answer: I would use the ls command to see a list of the files/folders in my current folder.
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
        Answer: I can use git rm to remove the file, however, I do have to be careful because there is no reminder or warning prompt that appears with this command. Once the file is removed, it is gone for good.
    34. Why should I use version control? 
        Answer: Version control allows teammembers to branch and merge, essentially working on multiple streams of work independently, while later merging that work together after verifying that the streams of work from each branch do not conflict. Work can flow faster and errors can be isolated and traced more quickly.
    35. How often should I commit to github?
        Answer: There seems to be a plurality of opinions, with some developers committing based on time, by the day, the hour, or half hour, and othe developers committing by the feature, based on writing working code that passes test, or fixing a typo or bug. If working on a team, it would be effective to have an accepted teamwide standard for when to commit.
    36. What is the command we would use to push our repo up to github? 
        Answer: The command used to push our repository up to git would be git push.
    37. Walk me through Lambda's git flow. 
        Answer: We fork the repo, then clone the repo, create our own branch for the repo, add the repo change, commit the repo change with a helpful commit message, push the changes up to my Github repo, and submit a pull request to verify.