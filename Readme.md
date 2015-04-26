#Applied RequireJS
##Modular Javascript and Dependency Management for Fancy People.
####By your unsavory pal,
####Jeremy Wagner ([@malchata](http://twitter.com/malchata))

#####Authored in [reveal.js](http://lab.hakim.se/reveal-js/#/)
---

##Overview

This is a talk on RequireJS (http://requirejs.org), a JavaScript module loader and dependency manager for web applications.  The talk is segmented as such:

- Introduction.
- A brief history of the web.
- How we already modularize and load JavaScript in dependent fashion (even though we may not realize it.)
- Starting with RequireJS.
- The anatomy of a RequireJS module.
  * A simple RequireJS configuration.
  * `define()` versus `require()`
  * CDNs and fallbacks.
- Configuring RequireJs via `requirejs.config()`:
  * `baseUrl`
  * `deps`
  * `exports`
  * A short list and overview of other options such as `waitSeconds`, `urlArgs`, `bundles`, `config` and et cetera.
- How to use the RequireJS Optimizer:
  * Installation with `npm`
  * Building from the command line with a build profile.
  * Building with grunt.
  * Avoiding pitfalls with CDN paths.
  * Managing exclusions.
- An example of an app with RequireJS implemented (only shown at actual events, there is no video, unfortunately. I'm considering doing a simple screen recording and placing it into the presentation.)
- Resources:
  * Competing solutions (Browserify, LABjs)
  * Talk-specific resources.

---

##Talk Events

This presentation was given at the following dates and events:

**02/14/2015**: General Mills Code Camp v4.0.
**04/25/2015**: Twin Cities Code Camp Spring 2015.

If you have questions about this talk, corrections, amendments, or if you are organizing an event or conference where you think this talk would fit in nicely, feel free to DM me on Twitter at [@malchata](http://twitter.com/malchata).  I welcome any and all feedback and questions!

&mdash;Jeremy Wagner