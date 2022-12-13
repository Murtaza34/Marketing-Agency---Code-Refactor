# Horiseon - Marketing Agency (code refractor)

For this challenge I was tasked to refractor an existing code, improving it to a more accessible standards and optimize for search engines.

Throughout this project I learnt a lot about clean coding. Not only does it make the coding look appealing but it makes it easy to read, easy to maintain and easy to extend. I was able to Remove unnecessary ```<div>``` tags and replaced them with proper HTML Semantic elements. I also managed to remove a number of duplicated CSS rules. 

Commenting was really important in this project. The CSS starter code was quite puzzling; I had no idea what was what. Each section of the webpage was made significantly more understandable and coding-efficient by including a comment next to it.

## Before and After code cleaning

Before:

```html
<article class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="Lightbulb pulsing signals" />
```            

After:

```html
<div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" />
```

Before:

```css
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```

After: 

```css
aside.benefit-lead .benefit-brand .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```

## Deployed Application

Visit [deployed page](https://murtaza34.github.io/Marketing-Agency---Code-Refactor/).

![page](/assets/images/Horiseon%20webpage.jpg)

## Built with

* HTML
* CSS

<p align="right">(<a href="#readme-top">back to top</a>)</p>