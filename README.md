# gallery-page

 This gallery page was built using html, css and bootstrap.

 These are some of the problems I ran into while building this page and the solutions I came up with.

 The navbar was built using bootstrap. I ran into some problem changing the color of the navbar since it was built with bootstrap. To solve this problem, I created a custom class `navbar-custom` and modified it in my style.css to change the color to a color of my choice.
 After changing the background color, the next step was to fix the readability of the navbar text by changing the text theme from dark to light. Bootstrap navbar comes with either a `navbar-light` or `navbar-dark` representing the text theme which can be set depending on the navbar background. Because of the background color I chose, I changed my navbar text to `navbar-light` to make my lists readable.

 I needed a way to upload my picture with captions and small texts for each, so I used the `<figure>` element to display my pictures on the gallery page. This allowed me to add captions to my pictures and include small description paragraph for the pictures. I used `<figcaption>` to caption the images.

 For the links to my socials, I experienced a lot of trouble using fontawesome and ended up not being able to use it but I wanted the social media links to each have their logos instead of just hyperlinks. So I downloaded transparent png logos and resized them to smaller sizes.
 My first attempt to solve the problem was to make the images buttons by wrapping the `<img>` elements in `<button>` tags. This gave the logos an outline that looks like a button but I wanted the images to act like buttons not look like them.
 My second and final solution was to make the images clickable by wrapping them in the `<a>` tags instead of `<button>` tags like this:
 `<a href="https://www.instagram.com/lexxie.starr/?hl=en" target="#"><img src="images/pngguru.com (5).png" alt=""/></a>`
 `<a href="https://t.co/tPuBoYQC2b?amp=1" target="#"><img src="images/pngguru.com (6).png" alt=""/></a>/` This was how I achieved the clickable social media links in the page.
