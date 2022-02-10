# 01 HTML, CSS, and Git: Code Refactor

This is a refactor of an existing code base for the website of Horiseon, a marketing agency.
Horiseon's website shows off the services that they provide, such as search engine optimization and online reputation management.

This refactor focused on improvements to accessibility and long-term sustainability.
The new code also corrects some syntax errors.

## Link to website
https://patricklquirk.github.io/Module_1_Challenge/

## Image of website
```md
![alt text](assets/images/screenshot.png)
```

## Important Note
Initially when I did this project, I created the repository with everything except the README file still in the Develop folder.
This made it so that publishing the site did not work. In trying to deal with the problem, I ended up having to recreate the repository.
This unfortunately has made it so that the history of changes I made is no longer present. I apologize for this.
Due to this, I will include a discussion of the changes that I made here in the README. 
These are not necessarily listed in the order that I made them

## Accessibility Improvements
* Added alt attributes to the icons and images
* Changed the div tags to more descriptive tags
* Ensured that heading attributes were in sequential order
* Added a title to the page

## Sustainability Improvements
* Consolidated classes that had the same purposes.
* Removed the "header" class and replaced it with a header element selector (since I replaced the div element for that class with a header element). Likewise for the footer

## Built With
* HTML
* CSS

## Contribution
Original code from Horiseon. Refactored by Patrick Quirk