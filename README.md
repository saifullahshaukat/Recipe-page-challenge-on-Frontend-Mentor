# Recipe-page-challenge-on-Frontend-Mentor
Crafting a recipe page involved understanding requirements, structuring HTML, and styling with CSS. Content was carefully curated, while responsiveness and optimization were prioritized. Peer feedback and online resources were instrumental. The result: a user-friendly, visually appealing page that embodies the artistry of web development.

# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

1. **Body Styles**: Sets up the body element to use flexbox for layout, with the background color and margins reset.

2. **Main Container Styles**: Defines the styles for the main container, which contains the main content of the page. It uses flexbox to center its contents vertically and horizontally, sets a maximum width, and adds some spacing from the top of the page.

3. **Article Styles**: Styles for the article element, which likely contains the main content of the page, such as the recipe instructions and details. It sets padding to provide spacing around the content.

4. **Figure Image Styles**: Styles the images within figure elements, making them responsive by setting their width to 100% and ensuring they maintain their aspect ratio.

5. **Typography Styles**: Defines font styles for various text elements, including headings, paragraphs, and lists. It specifies font families, sizes, and colors for consistent typography throughout the page.

6. **Table Styles**: Styles for tables, including borders, padding, and font styles. It ensures that tables are displayed with proper borders and padding for readability.

7. **Media Query**: Includes a media query to adjust styles for smaller screens, such as mobile devices. It modifies the layout and styling to ensure a better user experience on smaller screens.

Overall, the CSS code is well-organized and structured, with clear comments and consistent naming conventions. It provides a cohesive set of styles for creating a visually appealing and functional web page for displaying recipe content.

### Screenshot
![DesktopScreenshot](https://github.com/saifullahshaukat/Recipe-page-challenge-on-Frontend-Mentor/assets/157408050/3bb990e5-8045-4882-9811-6f4ef946c9cf)

### Links

- Solution URL: [Github](https://github.com/saifullahshaukat)

## My process

I started by structuring the HTML document, including necessary tags such as `<html>`, `<head>`, and `<body>`. Then, I identified the main components of the page, such as the recipe image, title, preparation steps, ingredients, instructions, and nutrition information, and used appropriate HTML tags to represent them.

After that, I populated the HTML structure with the actual content for the recipe page, including the recipe image, title, ingredients, instructions, and nutrition information.

Next, I opened a CSS file or `<style>` tag within the HTML document to apply styles to the page. I set up general styles for the body, such as background color and font settings, and used classes and IDs to target specific elements and apply styling accordingly. I applied styles for typography, colors, spacing, borders, and any other visual elements needed to achieve the desired layout and appearance. I tested and adjusted the styles as necessary to ensure the page looked good on different screen sizes and devices.

I linked custom fonts in the `<head>` section of the HTML document using Google Fonts or other font providers.

Then, I made the page responsive using media queries to adapt the layout for different screen sizes. I tested the responsiveness of the page by resizing the browser window or using browser developer tools to simulate various devices.

I reviewed the page layout and styling to ensure everything looked as expected and tested the page across different browsers and devices to ensure compatibility and responsiveness. I made any necessary adjustments or fixes based on testing results.

Once satisfied with the layout and styling, I added any final touches such as hover effects, animations, or additional content as needed.

I validated the HTML and CSS code to ensure it met the standards and was free of errors. I optimized the code for performance by minimizing file sizes, reducing unnecessary code, and optimizing images. I also considered accessibility features such as alt text for images and proper semantic HTML tags to improve accessibility for users with disabilities.

Finally, I deployed the page to a web server or hosting platform to make it accessible on the internet.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this project, I learned several key aspects of creating and styling a recipe page:

1. **HTML Structure**: I gained an understanding of how to structure an HTML document, including the proper use of tags such as `<html>`, `<head>`, and `<body>`. I also learned how to identify and organize different components of a webpage using appropriate HTML tags.

2. **Content Population**: I learned how to populate the HTML structure with actual content, including images, text, lists, and other elements necessary for a recipe page.

3. **CSS Styling**: Through this project, I learned how to apply CSS styles to HTML elements to achieve the desired layout and appearance. This included setting up general styles for the body, targeting specific elements using classes and IDs, and applying styles for typography, colors, spacing, borders, and other visual elements.

4. **Responsiveness**: I gained experience in making web pages responsive using media queries to adapt the layout for different screen sizes and devices. This involved testing the responsiveness of the page and making adjustments as needed to ensure compatibility across various devices.

5. **Final Touches and Optimization**: I learned how to add final touches such as hover effects, animations, and additional content to enhance the user experience. Additionally, I gained knowledge of HTML and CSS validation techniques and optimization strategies to improve code quality and performance.

One difficult part of the code may be the implementation of media queries for responsiveness. Here's a snippet demonstrating how media queries can be used to adjust the layout for different screen sizes:

```css
/* CSS for desktop screens */
@media only screen and (min-width: 768px) {
  /* Add desktop-specific styles here */
}

/* CSS for tablet screens */
@media only screen and (max-width: 767px) {
  /* Add tablet-specific styles here */
}

/* CSS for mobile screens */
@media only screen and (max-width: 480px) {
  /* Add mobile-specific styles here */
}
```

Understanding how to use media queries effectively and testing them across various devices can be challenging but is crucial for ensuring a seamless user experience across different screen sizes.

### Useful resources

- [Thenetninja](https://www.youtube.com/@NetNinja) - This channel really helped me for grasping the Basics of HTML CSS. I really liked this Channel and will use it going forward.

## Author

- Linkedin - [Saifullah Shaukat](https://pk.linkedin.com/in/deepistics)
- Frontend Mentor - [@saifullahshaukat](https://www.frontendmentor.io/profile/saifullahshaukat)

## Acknowledgments

I would like to express my gratitude to the following resources and individuals whose guidance and support were invaluable during the development of this project:

- Online tutorials and documentation for HTML and CSS, which provided foundational knowledge and guidance on best practices.
- Stack Overflow and other online communities for their wealth of knowledge and assistance in troubleshooting issues.
- My peers and colleagues who provided feedback and suggestions for improving the project.

Tips for Others:

1. **Start with a Plan**: Before diving into coding, take some time to outline the structure and design of your webpage. Consider the layout, content, and styling requirements to ensure a clear direction for your project.

2. **Learn HTML and CSS Basics**: Having a solid understanding of HTML and CSS fundamentals is essential for creating well-structured and visually appealing web pages. Take advantage of online tutorials, courses, and documentation to strengthen your skills in these areas.

3. **Practice Responsiveness**: Make responsiveness a priority in your web development projects. Experiment with media queries and test your pages across various devices and screen sizes to ensure a consistent user experience.

4. **Utilize Online Resources**: Don't hesitate to seek help from online resources such as tutorials, documentation, forums, and communities like Stack Overflow. These resources can provide valuable insights and solutions to common challenges.

5. **Iterate and Refine**: Web development is an iterative process. Continuously review and refine your code, incorporating feedback and making improvements along the way. This iterative approach will lead to better results and a deeper understanding of web development principles.

6. **Stay Curious and Keep Learning**: The field of web development is constantly evolving, so embrace a mindset of continuous learning. Stay curious about new technologies, trends, and best practices, and don't be afraid to experiment and try new things in your projects.

By following these tips and leveraging available resources, you can enhance your skills in web development and create impressive projects that meet modern standards and user expectations.
