# About Me: Zach Theis

This site is a combination between an online business card, a test for http and css techniques, and a showcase of those skills. It was created during my final semester at Raritan Valley Community College for Web Page Development 1. The specifics of each section will be enumerated below; more information on updates and online deployment can be found here:
[![Netlify Status](https://api.netlify.com/api/v1/badges/9f319380-0c88-4dcd-8afc-60600e4c2f71/deploy-status)](https://app.netlify.com/sites/about-me-zachtheis/deploys)

## Header

The Header consists of a logo, created through [Figma](https://www.figma.com), a navigation bar, and a small amount of text.

### Nav Bar

The navigation bar uses anchor tags to link to section ids throughout the page. The current design - with the exception of the font selection - was created by Prof Cynthia Teeters as part of a lecture. It will likely be redesigned before this project's completion.

### Logo

The Logo for this page is a simple monogram, created on [Figma](https://www.figma.com). Unlike the majority of the page, the font for this was Oleo Script, chosen because it's bold lines are legible in miniature while still retaining some degree of the script style shared by the rest of the text on the page. The colors selected were #be03e8 and #0357e8, chosen with [Session's College color calculator](https://www.sessions.edu/color-calculator/) for their complimentary nature with the background color of the body.

## Body

The main body of the website consists of a hero image, a bio, a phot gallery, an embedded video, a blog, and a contact form. These subsections will be discussed below, but because the color and font choices are common to all of them, I will address them here.

Five colors were chosen for this site: dark purple (#4d178f), light(er) purple (#8339db), dark green (#0b8f31), light green (#23db57), and tan (#dabb90). All were run past a filter for contrast and accessibility and, while the two purple shades and two green shades would be too close to use as background and text pairs, the overall color scheme of the website passed all tests. I selected dark purple as the background in order to provide the best contrast for a font color; I decided light green would have the best contrast with the dark purple background. Tan is used as the background color for elements that I wanted to highligh in their own box such as the photos in the gallery. Dark green is used as a thick border element on boxes to provide distinction against the dark purple background. The light purple is used very sparingly, only to provide small contrasting borders or textured effects.

The two fonts used on this site are Grenze and Grenze Gotish. Grenze makes up the bulk of the text; it is a serif font and so looks somewhat decorative, but it lacks the embellishments that would make smaller text difficult to read. Grenze Gotish, on the other hand, is a cursive font with plenty of decoration, perfect for the larger headers.

### Hero

The hero section consists simply of an avatar, my name, and my location. The avatar image was generated through [Avatar Generator](https://getavataaars.com/). This was my introduction into embedding images in a web page.

### Bio

The bio section is a bullet point list of a few facts about me, which will be updated shortly. This section uses the display: flex, flex-direction: column, and align-items: left properties to organize the lists.

### Gallery

My first foray into responsive design, the photo gallery's layout changes on devices with different size screens. On small screens, such as iPhones, images are contained in a tan box with a thick dark green border with a border-radius on all corners and a slight box-shadow. The images have a caption describing them below the picture. On slighly larger devices, such as iPads, the caption moves to the right of the image, centered horizontally and vertically in a grid column that takes up 1/3 of the box. On full screens, the tan box with the green border disappears. The images still have a shadow, but are now laid out horizontally instead of vertically. The captions appear flush to the bottom of the image in a tan box.

This section displays the grid and flexbox display properties, as well as media queries.

### Video

The video footage embedded in this section is free use footage from [Pexels](https://www.pexels.com/) with audio I recorded and spliced. The video container has a thick green outline and a shadow to set it apart from the background. I elected to keep the caption slightly separated from the video, as so few words would look silly in a box nearly the entire width of the screen.

### Blog

This section will be updated shortly.

### Contact Form

As this site has been deployed on [Netlify](https://www.netlify.com), the contact form will actually accept and store submissions. The submit button has both a hover and an active effect on it to make it clear when it is being highlighted and "pushed."

I made a slight deviation from my color scheme for the text in the dark green legends, as the other colors were hard to read. I kept with a similar pallet and selected a lighter purple (rgb 187, 154, 224) that would have more contrast against the background.

# Citations

Video footage by [Åke Wall from Pexels](https://www.pexels.com/video/a-person-walking-in-dark-forest-5582521/).

[Demo: CSS image hover effects](https://codepen.io/nxworld/pen/ZYNOBZ)

[W3: How To - Image Hover Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp)

[10 Simple CSS Hover Effects](https://thebrandsmen.com/css-image-hover-effects/)
