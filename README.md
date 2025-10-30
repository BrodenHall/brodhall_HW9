# brodhall_HW9
Homework 9 web forms
a. Description of the Project

This project is a four-page responsive web form built with Bootstrap 5.3 and Font Awesome, hosted as an Azure Static Web App. The form collects general student information and displays the responses on a confirmation page, demonstrating proper form design, validation, responsiveness, and accessibility.

b. How My Web Form Conforms to Best Practices for Forms

My web form follows several best practices to ensure clarity, usability, and consistency for all users. I broke the form into two smaller pages to reduce cognitive load and help users focus on one group of questions at a time. Each page clearly communicates its purpose using meaningful headings and brief instructions, which keeps users oriented as they progress through the form.

Every input field is properly labeled, and related options like radio buttons and checkboxes are grouped with a <fieldset> and <legend> element for clear context. Required fields are indicated with an asterisk and validated using HTML5’s built-in required attribute and Bootstrap’s validation feedback. This approach gives users immediate, clear feedback on what’s missing or invalid without needing to reload the page. I also used autofocus on the first field so users can start typing right away, minimizing extra clicks.

I incorporated a tooltip icon using Font Awesome to provide optional help text without cluttering the page. The layout uses Bootstrap’s responsive grid, ensuring the form automatically adapts to different screen sizes—from large desktops to mobile devices—without horizontal scrolling. Overall, the form uses plain, concise language and predictable navigation, which together represent best practices for an intuitive web form.

c. How My Form Provides for User Accessibility

Accessibility was a top priority in this project. I followed WCAG 2.1 Level AA standards to make sure the form is usable by everyone, including keyboard and screen-reader users. Each input has a descriptive label, and grouped fields use semantic HTML to provide structure that assistive technologies can interpret correctly. I included a skip-to-content link, visible focus indicators, and ensured all interactive elements can be navigated with the keyboard alone. Color contrast meets or exceeds the 4.5:1 ratio for regular text, and error feedback is provided through text instead of color alone. The tooltip is accessible via both mouse and keyboard focus, and the site layout reflows naturally down to 320 px screen widths. These choices make the form compliant, usable, and inclusive for all users.