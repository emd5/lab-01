# Lab 01: SMACSS and Responsive Web Design

## Overview

In lab today, you will be building a single responsive webpage based off of the provided design comp assets. These contain images of what you are striving to build in HTML and CSS, so be sure to open them up and keep them handy, but note that they are not for actual use on the page. You can also print out these comps and use them to mark up and sketch out page structure.

Your document must be designed in a mobile-first approach and must be responsive when the screen size changes and the page is refreshed. The details of the media query specifications are up to you, but your breakpoint must be at 768 pixels.

## Author

Liz Mahoney

## Feature #2 Create Desktop/Mobile Viewports

- [x] Create a new repository named lab-01.
- [x] Work on a non-master branch.
- [x] Use good HTML structure to scaffold this site, using semantic elements where possible.
- [x] Container elements (a box outside of your content box that might contain multiple content boxes) are very useful in managing layout. You will need to think about the relationship between parent and child / descendant elements as well as the order in which you place them in the HTML. Be thoughtful about your layout strategy.
- [x]  Add a reset.css file to your project, like this one.
- [x]  Use SMACSS-style modularity to organize your CSS.
- [x] Style the page using float-based layout to reflect the comp images provided as closely as possible. The only text you should have in each box is the identifying letter, which should be centered horizontally and vertically.
- [x]  For the desktop view, the content should be inside of a channel that is a maximum of 960 pixels wide and is centered on wider screen sizes.
- [x] Each box should have a unique background color in mobile view and in desktop view. We are not working with jQuery events yet, so these changes should be observed when the screen size changes and the page is refreshed.

## Feature #2: Responsive design 4/29/19

Why are we implementing this feature?

- [x] As a user, I want the dimensions and colors of the application to change so that I can have a unique view in desktop, mobile, and tablet viewports.
- [x] Use flex box or CSS grids for styling this application.
Use relative units so the elements scale proportionally when the viewport dimensions change.
- [x] Use at least two breakpoints and change the background colors of each box. There should be three possible views: desktop, tablet, and mobile device. You may choose the exact pixel values for each breakpoint.