# Homework 1 — Joshua Jones

A single-page personal homepage for CSC 4370 at Georgia State University.
Uses HTML and an external CSS stylesheet, with no JavaScript or frameworks.

## Open locally
Keep index.html, styles.css, and the images folder together. Open index.html in a browser.

## Before submission
- Review the biographical text and change anything you want worded differently.
- An original SVG initials graphic is included as the permitted profile placeholder.
- Validate index.html at https://validator.w3.org/ using file upload or direct input.
- Validate styles.css at https://jigsaw.w3.org/css-validator/ using file upload or direct input.
- Test in Chrome, Firefox, Safari, and Edge, including a narrow/mobile view.
- Upload index.html, styles.css, and images/ to ~/web/hw1/ on Codd as instructed.
- Verify the live URL: https://codd.cs.gsu.edu/~jjones552/web/hw1/index.html
- Upload the source files to your GitHub repository.
- Create submission.txt containing your name, tested Codd URL, and actual GitHub repository URL.
- Submit only that .txt file to iCollege, not the ZIP.

## Structure and learning notes
- header/nav: navigation anchors point to section IDs.
- main: profile, about, coursework, interests, and contact sections.
- figure/img: local profile image with descriptive alternative text.
- CSS Grid lays out the hero and project cards; media queries stack them on smaller screens.
- Classes style reusable groups; IDs identify navigation destinations.
- CSS focus outlines and a skip link support keyboard navigation.

Validation: W3C HTML checker returned no messages. W3C CSS validator returned valid=true with zero errors and warnings. Internal anchors, local assets, semantic elements, and image alt text checked. Browser visual/cross-browser checks, deployment, and submission still remain.
