# Matt Marsico's Portfolio Website
## Why Build a Portfolio Website
1. Greater control over how I present my projects. 
2. Track and share my learning through blog posts.
3. Cohesive platform for showcasing all aspects of my life.

## Tech Stack
In previous years, I have built this site in HTML, CSS, and JS, then
rewrote it with React, and have finally settled on using a static site
generator. As much as I support the idea of creating something on your own,
I would rather utilize my time for other projects I am working on. This
website will just function without too much additional work and allow me to
focus on content rather than development.

I am using the [Hugo](https://gohugo.io/) static site generator. For background, this is a tool
written in [Go](https://go.dev/) that creates flexible and performant websites.

## CI/CD
The purpose of portfolio website is to showcase important aspects of one's life. Since there is
a massive focus on content, I wanted to make it as easy as possible to update the content of the page.
I decided to use CI/CD with my Github repository and AWS Amplify. This means that whenever I make
changes to the repository, the changes will populate in the website, minimizing the amount of work
I need to do.
