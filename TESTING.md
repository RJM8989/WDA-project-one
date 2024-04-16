# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.


## Code Validation

### HTML

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FRJM8989.github.io%2FWDA-project-one%2Findex.html) | ![screenshot](documentation/validation/html-validation-home.png) | Section lacks header h2-h6 warning |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FRJM8989.github.io%2FWDA-project-one%2Fcontact.html) | ![screenshot](documentation/validation/html-validation-contact.png) | obsolete iframe warnings |
| Pricelist | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FRJM8989.github.io%2FWDA-project-one%2Fpricelist.html) | ![screenshot](documentation/validation/html-validation-quiz.png) | Pass: No Errors |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.


| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2FRJM8989.github.io%2FWDA-project-one) | ![screenshot](assets/Documentation/Validation/css-validation-style.png) | Errors: Font Awesome CSS |


## Browser Compatibility


I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | About | Contact | etc | Notes |
| --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](assets/Documentation/chrome-home.png) | ![screenshot](assets/Documentation/chrome-contact.png) | ![screenshot](assets/Documentation/chrome-pricelist.png) | Minor CSS differences |
| Safari | ![screenshot](assets/Documentation/safari-home.png) | ![screenshot](assets/Documentation/safari-contact.png) | ![screenshot](assets/Documentation/safari-pricelist.png) | Minor CSS differences |
| Opera | ![screenshot](assets/Documentation/opera-home.png) | ![screenshot](assets/Documentation/opera-contact.png) | ![screenshot](assets/Documentation/opera-pricelist.png) | Minor differences |


## Responsiveness

Sample responsiveness testing documentation:


I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | About | Contact | etc | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile | ![screenshot](assets/Documentation/Responsiveness/responsive-mobile-home.png) | ![screenshot](assets/Documentation/Responsiveness/responsive-mobile-contact.png) | ![screenshot](assets/Documentation/Responsiveness/responsive-mobile-pricelist.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](assets/Documentation/Responsiveness/responsive-tablet-home.png) | ![screenshot](assets/Documentation/Responsiveness/responsive-tablet-contact.png) | ![screenshot](assets/Documentation/Responsiveness/responsive-tablet-pricelist.png) | Works as expected |
| Desktop | ![screenshot](assets/Documentation/Responsiveness/responsive-desktop-home.png) | ![screenshot](assets/Documentation/Responsiveness/responsive-desktop-contact.png) | ![screenshot](assets/Documentation/Responsiveness/responsive-desktop-pricelist.png) | Works as expected |


## Lighthouse Audit


I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](assets/Documentation/Lighthouse/lighthouse-home-mobile.png) | ![screenshot](assets/Documentation/Lighthouse/lighthouse-contact-desktop.png) | Slow response time due to large images|
| Contact | ![screenshot](assets/Documentation/Lighthouse/lighthouse-contact-mobile.png) | ![screenshot](assets/Documentation/Lighthouse/lighthouse-contact-desktop.png) | Slow response time due to large images |
| Gallery | ![screenshot](assets/Documentation/Lighthouse/lighthouse-pricelist-mobile.png) | ![screenshot](assets/Documentation/Lighthouse/lighthouse-desktop-pricelist.png) | Slow response time due to large images |


## User Story Testing


| User Story | Screenshot |
| --- | --- |
|As a new site user, I want to be able to find the location I need quickly so that I don’t have to waste time browsing Google Maps.| ![screenshot](assets/Documentation/Features/feature01.png) |
|As a new site user, I want to be able to find the price list quickly so that I can find the prices of the services offered.| ![screenshot](assets/Documentation/Features/feature02.png) |
|-As a new site user, I want to be able to see different hairstyles so that I can see the haircuts I would prefer..| ![screenshot](assets/Documentation/Features/feature03.png) |
|As a new site user, I would like to you the contact form, so that I can enquire about of one the services offered.| ![screenshot](assets/Documentation/Features/feature04.png) |
|As a new site user, I would like to use the social media links, so that I can follow the business online.| ![screenshot](assets/Documentation/Features/feature05.png) |
|As a returning site user, I would like to be able to book an appointment, the booking form would allow me to do this.| ![screenshot](assets/Documentation/Features/feature06.png) |
|As a returning site user would like to use the social media links so that I can keep updated on the business online.| ![screenshot](assets/Documentation/Features/feature05.png) |
|As a returning site user, I want to be able to see different hairstyles so that I can see the haircuts I would prefer.| ![screenshot](assets/Documentation/Features/feature03.png) |
|As a returning site user, I want to be able to find the price-list I need quickly so that compare the prices of the services offered.| ![screenshot](assets/Documentation/Features/feature02.png) |



## Bugs


- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bugs/bug01.png)

    - To fix this, I _____________________.

- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

    ![screenshot](documentation/bugs/bug02.png)

    - To fix this, I _____________________.

- Python `'ModuleNotFoundError'` when trying to import module from imported package

    ![screenshot](documentation/bugs/bug03.png)

    - To fix this, I _____________________.

- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

    ![screenshot](documentation/bugs/bug04.png)

    - To fix this, I _____________________.

- Python `E501 line too long` (93 > 79 characters)

    ![screenshot](documentation/bugs/bug04.png)

    - To fix this, I _____________________.

## Unfixed Bugs

- Background colour in HTML and not CSS

    ![screenshot](assets/Documentation/unfixed-bug01.png)

    - Attempted fix: I tried to put the background colour into CSS as per standard practice, but it creates a clash of styles on the index page.



> [!NOTE]  
> There are no remaining bugs that I am aware of.
