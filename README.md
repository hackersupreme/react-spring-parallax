# React Spring Parallax Vertical & Horizontal Example

Contents
- Overview
- Live Site
- Installation
- Documentation
- Resources / Contact Info

## Overview

[React-Spring](https://www.react-spring.io/) is a spring based animation library in react.js. It comes with a hooks API and a render-props API. 

The spring-based physics of the library works really well with a parallax. The movement is very fluid and feels very natural. 

In the render-props API there are some parallax components to work with. This project provides two examples of pages that use those components.

One example is a vertical parallax with an emphasis on story-telling. The other example is a horizontal parallax that simulates a more app-like feel.

This is some example code from the [official documentation](https://www.react-spring.io/docs/props/parallax).
```
<Parallax pages={3} scrolling={false} horizontal ref={ref => (this.parallax = ref)}>
  <ParallaxLayer offset={0} speed={0.5}>
    <span onClick={() => this.parallax.scrollTo(1)}>Layers can contain anything</span>
  </ParallaxLayer>
</Parallax>
```
Check out the live site or download the files and host them on a local server to see the parallax in action!

## Live Site

http://react-spring.hackersupreme.com/parallax

## Installation

These steps assume you have [Gatsby.js](https://www.gatsbyjs.org/) and [Node.js](https://nodejs.org/en/) installed on your computer.

1. Create local directory for the project to live in
2. Download the files into that directory
3. Use a [cli](https://www.w3schools.com/whatis/whatis_cli.asp) and navigate into that directory
4. Use `npm install` to download the necessary node modules
5. Use `gatsby develop` to launch the server

## Documentation

The library has two parallax components to work with, `Parallax` and `ParallaxLayer`. 

**Parallax**

The `Parallax` component is the container component for the parallax. Its attributes define the parameters for the parallax, such as:
- How many pages there are 
- Whether it's horizontal or vertical
- If scrolling is enabled
- Spring configuration

Note: the `Parallax` component should be the container element for the entire page. Placing it among sibling elements will get you a double scroll bar.


**ParallaxLayer**

The `ParallaxLayer` component represents a slide on the parallax and should be a child of the `Parallax` component. Its attributes define the parameters for how this slide and the children it contains moves within the parallax. The parameters include:
- Offset from the top of the parallax
  - ie which page it is located within the parallax
- Slide Speed
- How the slide defines a page relative to the viewport
  - default is that one page equals 100% of width/height


**CSS Modules**

I use CSS modules to style the components in this project. If you are unfamiliar with CSS modules, I'd check out [their website](https://github.com/css-modules/css-modules)! It's a good way to localize css to the component you want to apply it to. It also comes bundled with Gatsby.js.

If you don't want to read into the documentation, it is pretty simple to understand.

I define css classes and their styles in a `filename.module.css` file and import that file into the file my React component is defined in. When you import the `filename.module.css` file those styles are represented as an object.

For example:

_filename.module.css_
```
.className {
  background: red;
}
```
_componentName.js_
`import Styles from './filename.module.css'`

`<div className={Styles.className} />`

###### Vertical

To get to the vertical example, go to http://react-spring.hackersupreme.com/parallax/vertical.

I found the vertical parallax to benefit from scrolling being enabled. The scrolling showcases the fluidity of the spring-based parallax. Since the scrolling feels so natural and easy, the content of the page should reward that ease. 

I spaced content out over 


## Resources

###### Email

jeffgsch@gmail.com

###### Website

http://hackersupreme.com

###### Resources



