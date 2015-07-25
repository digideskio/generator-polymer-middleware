# generator-polymer-express

Yoeman Generator for express-polymer with support for Polymer 1.0, express as server-side
router, and pure-html and jade templates.


## Usage

### Generate application interactively (supports jade or html)

	yo polymer-express

## NOTE: THE FOLLOWING IS INCOMPLETE 
### Generate an element interactively (supports jaded elements or normal polymer elements)

	yo polymer-express:el <element-name>


## Introduction


This is a simple yeoman polymer+express (+jade) generator for Google's opinionated Polymer 1.0
web-components based applications. (try saying that three times over).

It utilizes gulp for code-twiddling.

It interweaves Polymer and Express in a way that actually works with both paradigms (that's 
mostly thanks to express being highly unopinionated).

Currently there are two flavors of front-end generators available:

	1) html
	2) jade

and there are two starting templates:

	1) minimal
	2) polymer-starter-kit

## Coding engines


### Jade
Some people like to code in jade (I may be becoming one of them, but haven't done anything
extensive in it) and it's the express way, and I was merging express, so I couldn't not do 
jade.

### HTML
Some people only want to work in html, they like closing tags and verbosity
keeping the </> movement is alive -- and I am currently one of them (which makes typing this
into a markdown document kind of ironic).  For those of us, that do not want to template in 
jade, there is the html option


### Examples

The included minimal template is exactly that, a minimal example of a polymer app running
along with express as the server-side router.  The client-side routing is done using page.js;


The include polymer-starter-kit is diablorized from Polymer yeoman package, and express is
grafted on top with appropriate changes to gulp


