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

The `Parallax` component is the container component for the parallax. Its attributes define the parameters for the parallax, such as:
- How many pages there are 
  - eg `pages={3}`
- Whether it's horizontal or vertical
  - `vertical`
 


###### Vertical

To get to the vertical example, go to http://react-spring.hackersupreme.com/parallax/vertical.



## Resources

###### Email

jeffgsch@gmail.com

###### Website

http://hackersupreme.com

###### Resources



