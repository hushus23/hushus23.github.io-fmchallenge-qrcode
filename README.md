# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](/images/Screenshot_qr-code.jpeg)

<!-- Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above. -->

### Links

- Solution URL: [Add solution URL here]
- Live Site URL: [Add live site URL here]
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
<!-- - Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles -->

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<body>
 <div class="qr-card">
  <img src="/images/image-qr-code.png" alt="barcode">
  <div class="caption">
    <h1>Improve your front-end skills by building projects</h1>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
  </div>
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. </br>
    Coded by <a href="#">Husna</a>.
  </div>
</body>
```
```css
 body{
      margin-left: auto;
      margin-right: auto;
      padding: 0%;
      align-content: center;
      font-family: "Outfit", sans-serif;
      background-color: hsl(212, 45%, 89%) 
    }

    .qr-card{
      margin-left: auto;
      margin-right: auto;
      margin-top: 10rem;
      overflow: hidden;
      align-self: center;
      padding: 0.5rem;
      position: relative;
      background-color: #ffffff;
      text-align: center;
      border-radius: 0.5rem;
      max-width: 200px;
      box-shadow:
      0 20px 25px -5px rgba(0, 0, 0, 0.1),
      0 10px 10px -5px rgba(0, 0, 0, 0.04);
    }

    img{
      display: flex;
      margin-left: auto;
      margin-right: auto;
      background-color: hsl(0, 0%, 100%);
      flex-shrink: 0;
      justify-content: center;
      align-items: center;
      width: 12rem;
      height: 12rem;
      border-radius: 0.5rem;
    }

    .caption {
      align-self: center;
      margin-top: 0.75rem;
      text-align: center;
      max-width: 200px;
    }

    h1{
      color: hsl(218, 44%, 22%);
      font-size: 1rem;
      font-weight: 800;
      line-height: 1.5rem;
    }

    p{
      margin-top: 0.5rem;
      color: hsl(216, 15%, 48%);
      font-size: 0.75rem;
      line-height: 1.25rem;
    }

    .attribution{
      position: sticky;
      align-items: flex-end;
      text-align: right;
      font-size: 0.5rem;
      padding: 20px;
      margin-top: 5rem auto;
      bottom:0;
    }

```
<!-- ```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
``` -->

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

<!-- Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect. -->



### Useful resources

<!-- - [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept. -->


## Author

- Frontend Mentor - [(https://www.frontendmentor.io/profile/hushus23)]
<!-- - Twitter - [@yourusername](https://www.twitter.com/yourusername) -->

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

