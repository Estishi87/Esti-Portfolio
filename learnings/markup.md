<div align="center">
 
 ![image](https://github.com/Estishi87/Esti-Portfolio/assets/125391502/3637b92c-0fdc-40d4-8de3-403497ee0d65)
 <br ></div>

# 1. Structure a site using semantic HTML to aid accessibility

In my Sky & Fly agency website project, I employed semantic HTML elements to create a well-structured and accessible website. Here are some of the key elements I used:

- `<header>`: Used for the top section of each page, which typically includes the website's logo, main navigation menu, and introductory content.

- `<nav>`: Employed to define the website's navigation menu, providing easy access to different sections.

- `<section>`: Used to group content thematically within each page, improving readability and organization.

- `<footer>`: Placed at the bottom of each page to include metadata, copyright information, contact details, and related links.

- `<main>`: Wrapped the main content of each page within a `<main>` element to signify its importance.

#### snippet of my HTML code that demonstrates the use of some of the semantic HTML elements mentioned:

 ```html
<header class="header">
      <div class="header-container">
        <div id="header-branding">
          <a href="index.html#home" class="branding-link">
            <img src="images/logo.jpeg" alt="agency logo"
          /></a>
        </div>
        <div id="header-nav-container">
          <nav id="header-nav">
            <ul id="header-nav-menu">
              <li class="menu-item">
                <a href="#home" class="active" class="nav-link">Home</a>
              </li>
              <li class="menu-item">
                <a href="#about" class="nav-link">About</a>
              </li>
              <li class="menu-item">
                <a href="#team" class="nav-link">Team</a>
              </li>
              <li class="menu-item">
                <a href="#fleet" class="nav-link">Fleet</a>
              </li>
              <li class="menu-item">
                <a href="#contact" class="nav-link">Contact</a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </header>
```

By utilizing these semantic elements, I enhanced the website's structure, accessibility, and search engine optimization (SEO), ensuring a better user experience for all visitors.



# 2. Ensure a web page is readable for screen readers

In our web development project, we paid special attention to making our web pages readable for screen readers and ensuring an inclusive browsing experience for all users, including those with visual impairments. One of the techniques we used to enhance screen reader accessibility is the tabindex attribute.

### Tabindex Attribute
The tabindex attribute allows us to control the order in which elements receive keyboard focus when a user navigates a web page using the "Tab" key. By strategically applying the tabindex attribute, we can ensure that screen readers and keyboard users can navigate and interact with our content in a logical and meaningful way.

For example:

```html
<div class="card" tabindex="0">
    <!-- Content of the card -->
</div>
```
In the above code snippet, we've added a tabindex attribute to a <div> element with the class "card." This allows users to focus on the "card" element when navigating the page using the keyboard. The tabindex="0" value means that the element will receive keyboard focus in the order it appears in the HTML source code.

By using tabindex appropriately and ensuring that the focus order follows a logical flow, we make it easier for screen reader users to understand and interact with our web pages, providing a more accessible and inclusive user experience.


# 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

In our web development project, we prioritized ensuring that our user interface (UI) maintains sufficient color contrast to ensure a comfortable and inclusive browsing experience for all users. We chose light colors as part of our design strategy to create a visually pleasing and accessible user interface.

## Using Light Colors
![image](https://github.com/Estishi87/Esti-Portfolio/assets/125391502/5be7e097-9900-4ec2-b613-9ae110775b5c)


We deliberately selected a color palette that incorporates light colors to enhance the readability and usability of our website. Light colors not only contribute to an aesthetically pleasing design but also help improve the overall user experience, especially for individuals with visual impairments.

By opting for light colors, we achieve the following benefits:

1. **Improved Legibility**: Light backgrounds with dark text or content elements contribute to better legibility and readability, making it easier for users to consume information.

2. **Enhanced Accessibility**: Light color combinations often result in higher contrast ratios, which are critical for users with low vision or color blindness. This ensures that text and content stand out clearly against the background.

3. **Reduced Eye Strain**: Light color schemes are generally less likely to cause eye strain and fatigue during extended periods of reading or browsing.

## Prioritizing User Comfort

Our design approach underscores the importance of user comfort and accessibility. By using light colors, we aim to provide a comfortable and enjoyable viewing experience for all users, regardless of their visual abilities. This commitment to color contrast aligns with our goal of making our website accessible to as many people as possible.

In summary, our choice of light colors is a deliberate decision to enhance color contrast, legibility, and overall accessibility. We believe that everyone should be able to perceive and engage with our website comfortably, and our color scheme plays a vital role in achieving that goal.


# 4. Use various tools to check that our website meets accessibility criteria

In our web development project, ensuring accessibility is a priority. We have employed various tools and techniques to check that our website meets accessibility criteria, providing an inclusive experience for all users, including those with disabilities.

## Tabindex Attribute (As Mentioned in Point 2)

As previously mentioned, we used the `tabindex` attribute strategically to control the order in which elements receive keyboard focus, ensuring a logical and meaningful navigation experience for screen reader users and keyboard users.

## Evaluation with Online Tools

To further ensure accessibility, we utilized online tools to evaluate our website's compliance with accessibility standards. One of the tools we relied on is [Easy Agile's Accessibility Checker](https://blog.easyagile.com/how-to-write-good-user-stories-in-agile-software-development-d4b25356b604).

## Meeting Acceptance Criteria

In addition to using tools, we also considered specific acceptance criteria to ensure accessibility throughout the project. Here are some examples of the acceptance criteria we addressed:

1. **Navigation Menu**: The navigation menu is designed and tested to be fully navigable and usable with keyboard controls and screen readers.

2. **'About Us' Section**: We ensured that the 'About Us' section contains descriptive and meaningful content to enhance comprehension.

3. **Contact Form**: The contact form is designed with accessible labels, and form fields are marked appropriately for screen readers.

4. **Form Submission**: Users cannot submit the form without completing all mandatory fields, including name, company name, and email address. This ensures that important information is not omitted.

5. **User Interaction**: Information from the form is not submitted until the user clicks a button, providing control and context to users.

By addressing these acceptance criteria and utilizing accessibility evaluation tools, we are committed to making our website accessible to all users, regardless of their abilities. Our goal is to provide an inclusive and user-friendly experience for everyone who visits our site.


# 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes

# 6. Demonstrate a mobile-first approach to building a website

# 7. Use CSS variables to apply repeated colours to HTML elements

# 8. Use CSS Flexbox to style children in a single-direction layout (ie a row or a column)

# 9. Use CSS Grid to style children in two-direction layout

# 10. Ensure our Git commit history tells a coherent story

# 11. Use the appropriate input types in HTML forms for gathering different types of information
