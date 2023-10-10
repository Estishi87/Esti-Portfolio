## 1. Structure a site using semantic HTML to aid accessibility

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



## 2. Ensure a web page is readable for screen readers

## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

## 4. Use various tools to check that our website meets accessibility criteria

## 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes

## 6. Demonstrate a mobile-first approach to building a website

## 7. Use CSS variables to apply repeated colours to HTML elements

## 8. Use CSS Flexbox to style children in a single-direction layout (ie a row or a column)

## 9. Use CSS Grid to style children in two-direction layout

## 10. Ensure our Git commit history tells a coherent story

## 11. Use the appropriate input types in HTML forms for gathering different types of information
