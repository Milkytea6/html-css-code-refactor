### code-refactor


## User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
## Acceptance Criteria
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## Summary

I received starter code for the Horiseon webpage. I was tasked with refactoring the code to a more clear and concise state. I started by changing the div elements in the HTML to semantic elements so it was clear what each section was for. Then I changed the CSS selectors to match the changes I made in the HTML. I also added in an id tag for one of the nav links. It was needed in order for the user to be redirected there where they clicked on the nav link in the header. In the CSS, I also grouped many of the selectors together since they were applying the same styles. Then went even further by just targeting every element of it's kind using the semantic elements I changed. Now the code for this webpage is much more concise and easy to understand.

## Link to Deployed Webpage

https://milkytea6.github.io/html-css-code-refactor/

## Sceenshot of Webpage

![Screenshot of deployed html-css-code-refactor](./assets/images/horiseon-code-refactor.png)