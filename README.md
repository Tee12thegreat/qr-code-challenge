# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents


  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  
- [Author](#author)




### Screenshot

![image](https://github.com/user-attachments/assets/15bfb4c3-d4b9-4e42-a6d4-4344ff7b780c)

### Links

- Solution URL: [Add solution URL here](https://github.com/Tee12thegreat/qr-code-challenge.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

i firstly learnt and implemented my version control using git and github. i then proceeded to write my html code then styled the page using CSS.

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

iv learnt how to size my webpage, adding an image to a webpage, how to size my image and make it fit properly to the container i created. iv also learnt how touse Git


```html
<h1>Some HTML code I'm proud of</h1>
 <div class="qr_code">
          <img src="./images/image-qr-code.png" alt="QR-CODE">
            <h2>
              <strong>Improve your front-end skills by building projects</strong>
            </h2>
            <h3>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</h3>
            Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
            Coded by <a href="https://github.com/Tee12thegreat/qr-code-challenge.git">Takomborerwa</a>.

      </div>
      
```
```css


:root {
    --white: hsl(0, 0%, 100%);
    --slate-300: hsl(212, 45%, 89%);
    --slate-500: hsl(216, 15%, 48%);
    --slate-900: hsl(218, 44%, 22%);
}

body{
    font-family: 'Outfit', sans-serif;
    background-color: var(--slate-300);
    overflow: hidden;
    height: 100%;
    margin-top: 2%;
    margin-bottom: 2%;
    

}
.qr_code{
    
    width: 20%;
    height: 40%;
    margin-top: 20%;
    margin: 0 auto;
    padding: 2%;
    background-color: var(--white);
    border-radius: 9px;
    
    
    
}
.qr_code img{
    width: 100%;
    height: auto;
    border-radius: 9px;
    overflow: auto;
}
.h3{
    font-size: 15px;
    align-content: center;
    font-weight: normal;
}


```

### Continued development

i want to deepen my knowledge on writing readable code, and how to play around with CSS


## Author

- Website - [Takomborerwa]()
- Frontend Mentor - [@Tee12thegreat](https://www.frontendmentor.io/profile/)




