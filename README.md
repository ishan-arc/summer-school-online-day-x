Documentation for Personal Portfolio Website

1. Explanation of HTML Elements:
- <!DOCTYPE html>: Declares the document type and version of HTML.
- <html>: Root element of the HTML document.
- <head>: Contains meta-information about the document like charset, title, and links.
- <meta>: Provides metadata such as character encoding and viewport settings.
- <title>: Sets the title of the webpage shown in the browser tab.
- <link>: Links external resources like favicon.
- <body>: Contains the visible content of the webpage.
- <header>: Defines the header section, usually containing the site title and navigation.
- <nav>: Defines a navigation menu with links.
- <ul> and <ol>: Unordered and ordered lists respectively.
- <li>: List item inside ul or ol.
- <h1> to <h6>: Heading elements with decreasing importance.
- <section>: Defines thematic grouping of content.
- <table>, <thead>, <tbody>, <tr>, <th>, <td>: Elements to create tables.
- <img>: Embeds an image with alt text for accessibility.
- <form>: Defines a form for user input.
- <fieldset> and <legend>: Group related form elements with a caption.
- <label>: Associates text labels with form inputs.
- <input>: Various types of user input fields.
- <textarea>: Multi-line text input.
- <button>: Clickable button.
- <footer>: Defines the footer section of the page.

2. Why Specific Input Types Were Chosen:
- text: For general text input like Name.
- email: To ensure the input is a valid email format.
- tel: For phone numbers, allowing numeric and special characters.
- textarea: For longer messages.
- checkbox: To allow multiple preferred contact methods.
- radio: To select one inquiry type.
- select (dropdown): To choose from predefined options.
- date: To select a date easily with a calendar UI.
- range: To select a value within a range using a slider.

3. Navigation Structure:
- The navigation menu is placed inside the <nav> element within the header.
- It uses an unordered list (<ul>) with list items (<li>) containing anchor (<a>) tags.
- Links connect the three pages: portfolio.html (Home), about.html (About Me), and contact.html (Contact).
- External links in about.html open in new tabs using target="_blank" and rel="noopener noreferrer" for security.

This structure ensures easy navigation and accessibility across the website.
