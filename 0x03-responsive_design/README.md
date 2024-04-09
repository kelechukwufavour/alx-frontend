# Project Readme

## Description
This project aims to enhance the CSS Advanced project by incorporating images and resolving issues related to the hero banner and container flexibility.

## Setup
1. Download the images provided in the CSS Advanced project and place them into the `images` directory at the root of the project.
2. Alternatively, use some basic assets from the `archive.zip` file.

## Tasks
### 0. Fix the Hero Banner
#### Description:
Due to changes made in the `article.html` page in the previous project, the hero banner's background is no longer visible. This task aims to rectify this issue.

#### Steps:
- Use the starter HTML and CSS provided in the project description.
- In the `01-styles.css` file:
  - Update the `background-position` property inside the `.hero-homepage` class selector to `65% 8rem`.
  - Update the `background-size` property inside the selector targeting the `.section-inner` class inside the `.section-hero` class to `90rem auto`.
  - Update the `min-height` property inside the selector targeting the `.section-inner` class inside the `.section-hero` class to `35vh`.

#### Final Rendering:
The hero section should resemble the provided example.

#### Repository:
- GitHub repository: [alx-frontend](https://github.com/alx-frontend)
- Directory: `0x03-responsive_design`
- Files: `01-styles.css`, `01-index.html`

### 1. Make the Container Flexible
#### Description:
This task involves making the container flexible by updating the `.container` selector in the `02-styles.css` file.

#### Steps:
- In the `02-styles.css` file, update the `.container` selector by changing `width` to `max-width`.
- Upon resizing the browser, the content should resize accordingly.

## Conclusion
By completing the tasks mentioned above, the project will achieve improved visual aesthetics and enhanced responsiveness.