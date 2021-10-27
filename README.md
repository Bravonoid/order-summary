# Frontend Mentor - Order summary card solution
This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Links
- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
This challenges helps me to implement from what i've learn before, especially about CSS Grid and Flexbox. As this is my first project, i am truly proud of myself after finishing this project. These are some of the highlights from what i've manage to create from scratch.

```html
<div class="selected">
  <div class="left">
    <div class="music"></div>
    <div class="content">
      <h2>Annual Plan</h2>
      <p class="price">$59.99/year</p>
    </div>
  </div>
  <div class="right">
    <a href="#" class="change">Change</a>
  </div>
</div>
```

```css
.selected{
    background-color: hsl(225, 99%, 98%);
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    margin-bottom: 36px;
}

.left{
    display: grid;
    grid-template-areas: 
        'logo title'
        'logo paragraph';
}

.selected .right{
    display: flex;
    justify-content: center;
    align-items:flex-start;
}
```
### Continued development
For further development, i am trying to be as comfortable as i could by maximizing CSS and HTML to create something that truly satisfy everyone, especially my own being. Besides that, i am looking forward to add Javascript to make my own web more alive.

### Useful resources
- [Web Programming UNPAS](https://www.youtube.com/c/WebProgrammingUNPAS/playlists) - This helped me a lot from HTML to CSS, well explained and detailed, mostly on CSS.

## Author
- Frontend Mentor - [@Bravonoid](https://www.frontendmentor.io/profile/Bravonoid)
- Twitter - [@dikibagast](https://twitter.com/dikibagast)