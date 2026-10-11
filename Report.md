# Week 3 Task: Integrating JavaScript for Interactive User Experience

## Introduction

The objective of this Week 3 project was to enhance a static responsive webpage by integrating JavaScript to create an interactive and user-friendly experience. HTML was used to create the structure of the webpage, CSS was used for styling and responsive design, and JavaScript was used to add dynamic functionality.

## JavaScript Features Implemented

Several interactive features were implemented using plain JavaScript. First, a responsive mobile navigation menu was created using an event listener. When the menu button is clicked, JavaScript adds or removes an active CSS class, allowing the navigation links to appear or disappear on smaller screens.

A dark and light mode feature was also implemented. The theme button uses JavaScript to toggle a CSS class on the body element. The button icon changes depending on the selected theme, providing visual feedback to the user.

The Learn More and Show More buttons dynamically display or hide additional content using DOM manipulation. Service cards also contain View Details buttons. When a user clicks one of these buttons, JavaScript identifies the selected service and displays a corresponding message.

Another important feature is contact form validation. JavaScript checks whether the name, email and message fields contain valid information before allowing the form to be submitted. Email format validation is performed using a regular expression, while the message is required to contain a minimum number of characters. Error messages are displayed dynamically when invalid input is entered.

## Challenges and Solutions

One challenge was ensuring that JavaScript interactions did not affect the responsive layout. This was solved by separating the JavaScript functionality from the CSS styling and using CSS classes for showing and hiding elements. Event listeners were also used instead of inline JavaScript, which keeps the code organized and easier to maintain.

## Conclusion

This project provided practical experience with DOM manipulation, event handling, form validation and dynamic content updates. The integration of HTML, CSS and JavaScript successfully transformed the static webpage into a more interactive and engaging user experience.