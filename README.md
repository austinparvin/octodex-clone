# Octodex Clone

This is a responsive website cloned after [https://octodex.github.com/](https://octodex.github.com/) 

# Objectives

- Build on your knowledge of HTML & CSS
- Implement, from scratch, a given design
- Understand HTML/CSS Layout
- Be able to place elements on a page where you want them.
- Use flexbox and grid techniques layout pages.
- Work with media queries to build a responsive page.

# Includes: 

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://www.w3schools.com/css/)
- [FLEXBOX](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [NETLIFY](https://docs.netlify.com/?_ga=2.56383019.1272475466.1587169866-1421079835.1583768648)

## Live Site

[LIVE SITE](https://octodex-clone-austinparvin.netlify.app/)

![Octo Clone](https://i.imgur.com/cq9X2XM.png)

## Featured Code

### Desktop CSS Media Query

```CSS
 @media (min-width: 1000px) {
  main {
    padding: 1rem;
    padding-top: 0;
    display: grid;
    grid-template-columns: 25% 25% 25% 25%;
    grid-template-rows: 50% 50%;
  }
  nav section {
    padding: 0;
  }
  section {
    padding: 0 1rem;
    margin-top: 0;
  }
  a.hide {
    display: flex;
    margin-left: 1rem;
    font-weight: normal;
  }
}
 ```
 
