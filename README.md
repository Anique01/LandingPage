# Landing Page Project

Note: To see my commit messages on the whole project please visit: [the place where I first started building this project](https://github.com/Anique01/FoundationsCourse_OdinProject/tree/main/LandingPage)

This project is part of [The Odin Project's Foundations](https://www.theodinproject.com/lessons/foundations-landing-page) course. For this assignment, I'll be creating a landing page based on a provided design, using HTML and CSS. The main goal is to put the skills I've learned so far into practice, including structuring content with HTML and styling with CSS.

## Project Features

- Replicating the design using HTML5 and CSS3
- Implementing layout elements like headers, sections, and footers
- Following the design structure and styling from the provided images
- Using a single stylesheet for all styling
- Customizing the content with personal images, text, and experimenting with fonts and colors

## Design

The project is based on two design images provided by The Odin Project:
- **Image One (Full Design):** Displays the complete layout of the landing page.
![Full Design](https://cdn.statically.io/gh/TheOdinProject/curriculum/81a5d553f4073e593d23a6ab00d50eef8620796d/foundations/html_css/project/imgs/01.png)
- **Image Two (Color and Fonts):** Shows the fonts and color scheme used in the design.
![Color and Fonts](https://cdn.statically.io/gh/TheOdinProject/curriculum/a38403e7d81cc8305af16ac48985cfbde87834d6/foundations/html_css/flexbox/project-landing-page/imgs/02.png)

The objective is to replicate the layout, fonts, and colors as closely as possible to match the design in these images.

## Technologies Used

- HTML
- CSS

## Problems Encountered and Solutions

*I will edit this section later to reflect any challenges I face during the project and how I resolve them.*

### 1. Navigation Color Matching

**Problem:**  
I had trouble figuring out how to get the navigation color to match the provided layout picture more accurately. Initially, I thought it had something to do with opacity.

**Solution:**  
After doing a quick Google search, I found out I could adjust the opacity of the text by using `opacity: ;`. I played around with the different numbers and came out on 0.7. This helped me achieve a closer match to the layout’s color.

### 2. Flexbox Alignment Issues

**Problem:**  
I had trouble figuring out how to get the flexbox to flex correctly. The layout was not aligning as expected, and some elements were not positioned properly.

**Solution:**  
After doing some Google research, I realized the issue was related to how I had structured my flex container and its child elements. By adjusting the `.left` and `.right` classes, I was able to correct the alignment and make the flexbox behave as intended.

### 3. Image and Text Alignment under Flexbox

**Problem:**  
I was having trouble aligning text directly under images while keeping the images in a horizontal line. Initially, I used flexbox for the layout, but the text wasn't aligning correctly beneath the images, and they were not grouped as intended.

**Solution:**  
After searching online for solutions, I couldn’t find a clear fix. I then asked ChatGPT for help, who explained that the issue was due to not grouping the image and text together as a single flex item. ChatGPT suggested wrapping each image and its corresponding text inside a container (`<div class="infoItem">`) and using `flex-direction: column` to stack them vertically within the flex container. This allowed me to keep the images aligned horizontally while positioning the text under each image correctly.

## Reflection

I really enjoyed this assignment as it gave me the opportunity to put what I've learned into practice. I started with writing all the HTML, which felt like the easiest part. Then, I moved on to CSS, where I quickly got through the navigation section. My main challenges came with flexbox alignment, particularly when trying to align images and text properly. But solving these problems helped me improve my CSS skills and gain more confidence in my ability to tackle layout issues. I also added a bit of my own styling to the project, which made it feel like my own creation while still staying true to the provided design.
