# Project 0: AJ's Bob Dylan

Web Programming with Python and JavaScript


## Overview

I have created a website with some information I want to keep track of of Bob Dylan, one of my poetry / literature idols. The website is divided into 4 pages:

- home
- about
- quotes
- gallery

The home page is the entry point / landing page of the site, with its title and some information about the purpose of the site.

In the about page, I aim to put some information about Dylan that is of interest to me. For the moment, this consists of a table of all the movies that Dylan has appeared in, with a column indicating if I have seen it yet.

The quotes page is a grid layout of quotation cards. These are either Dylan quotes made "outside the lyrics" as well as lyric quotes with song names. These quotes are based on what resonates with me, and not an exhaustive list of famous quotes. As I listen to more and more of his music, different lyrics jump out at me.

The gallery page is just a gallery of images I like related to Dylan.


## Stack and technology used

This is a pure front end website, using HTML5, CSS, SASS, Bootstrap 4 and some bootstrap javascript / jquery scripts. The scss is fully written in SASS and compiled to CSS. I have used various bootstrap layout utilities and some components (nav, jumbotron, table, grid).

## Further / future considerations that come to mind

- I would like to know how to use the nav component in a template so that I only have to write it once, and not copy and paste it into every page. However, without vue or such, I don't know how I would deal with applying / removing the active class. But I guess I have answered my own question.

- When the screen is shrunken the background image distorts and starts repeating, as well as the background gradient. I guess I need to change the styling of the background image for smaller screens.

- I would like to figure out how to allow my bootstrap grid to have different sized images in rows and overflow the rows instead of creating a new row after clearing all margins and paddings. If this makes sense.
