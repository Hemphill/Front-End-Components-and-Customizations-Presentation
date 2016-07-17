# Presentation Directions

Built using the HTML presentation framework [reveal.js](http://lab.hakim.se/reveal-js/)
and the [Yeoman](http://yeoman.io) generator [generator-reveal](https://github.com/slara/generator-reveal).

## Basic Usage


### Creating New Slides

From the terminal, pop in:

```sh
yo reveal:slide "Slide Title"
```

Available options:

```sh
--markdown --attributes --notes
```

Example:

`yo reveal:slide "Slide Title" --markdown`

_More information (i.e. option usage, vertical slides) available in the [generator-reveal documentation](https://github.com/slara/generator-reveal#slide)_



### Serving Slides (development)

```sh
grunt serve
```

Browser page should open to: `http://localhost:9000/`

### Github Pages Deployment

```sh
grunt deploy
```

_More information (e.g. setup directions) available in the [generator-reveal documentation](https://github.com/slara/generator-reveal)_

## Resources

- [reveal.js](http://lab.hakim.se/reveal-js/)
- [generator-reveal](https://github.com/slara/generator-reveal#github-pages-deployment)
- [Yeoman](http://yeoman.io)

This all assumes you're familiar with the typical [Node.js](https://nodejs.org/), [NPM](https://www.npmjs.com), & [Grunt](http://gruntjs.com) style front-end development setup.
