# mtm6201-final
1. Converting Figma Designs into Responsive Code

One of the biggest challenges was translating my high-fidelity Figma designs into clean, responsive HTML and CSS.
Many visual elements looked perfect in the mockup, but required careful layout adjustments when coding.

How I solved it:
I used Bootstrap’s grid system, media queries, and CSS customizations to make sure my design scaled correctly across mobile, tablet, and desktop screens.

2. Maintaining Visual Consistency Across All Pages

Because the project had multiple pages (Home, About, Get Involved), ensuring consistency in colors, typography, spacing, and component styling was challenging.

Solution:
I created reusable CSS classes, defined custom Bootstrap variables, and separated the navbar and footer into PHP include files to keep the layout uniform across all pages.

3. Image Optimization & Responsive Behavior

Some images were large, irregularly shaped, or had transparent backgrounds. Making them responsive without stretching or distortion required multiple tests.

Solution:
I resized images, exported them in optimized formats, and used object-fit, max-width, and responsive Bootstrap classes to ensure correct rendering.

4. Accessibility & W3C Validation Errors

Initially, the validator displayed errors such as missing alt attributes, illegal filename spaces, and warnings about sections lacking headings.

Solution:
I renamed all image files, added appropriate alt text, and used visually-hidden <h2> tags to improve accessibility while keeping the visual layout clean.

5. Integrating Decorative Graphics with Code Layout

Some design elements (stars, paw icons, badge circles, etc.) looked great in Figma but were difficult to position accurately in HTML.
Positioning them without breaking responsiveness was a challenge.

Solution:
I combined relative/absolute positioning and Bootstrap spacing utilities, and simplified certain elements to keep the code neat and stable on all screen sizes.

All images used in this project were either created by me or generated using AI-based tools such as Adobe Firefly / Midjourney / DALL·E. These images were modified, optimized, and resized to fit the needs of the website. No copyrighted or licensed stock images were used.

Wherever external assets were used (icons, decorative graphics), they were open-source or royalty-free resources and are listed below.