# External developers guide

## Working with Mono

This document aims to provide some information for development parties working with <a href="https://mono.company">Mono</a>.

### Mono goals

* We are primarily a design team; we don’t want to take over your developer role
* We want to assist you in tasks that concern design: icon exports, typography, alignment,…
* We understand that within a project your primary goal is to make the application work, and that you don’t always have the time for design details. We can assist with front-end code to aid you in that part
* Within each project would like to establish a good working relationship with the developing team, in order to guarantee a better end-result

### Mono coding preferences

* We use BEM and ITCSS when we have the choice
* Otherwise, we will accord to the coding style of the project. We have very extensive experience with Bootstrap.

### Code quality

* Within the project, it should be determined whether the purpose of the code is prototyping or production ready
  * If the code is prototyping only, we do not officially browser-test. We use Chrome and Safari for development, depending on the developer's preference.
  * If the code is meant to be production ready, we test for browser compatibility as agreed upon within the project

### On Javascript

* We primarily deliver HTML and CSS templates
* When we write Javascript, it is often for prototyping purposes. The actual implementation is up to you. What we write can serve as the inspiration for the implementation (i.e. by showing the timing of animations etc.)
* We might use plugins like select2, summernote and pikaday to explain concepts in our prototypes. We love to know your preferred set of plugins that work with your tech stack, so we can think ahead how these would fit into the overall design.

### Solutions for communication

We prefer using Git, combined with Github and Github issues.

Otherwise, we will accord to other communication solutions (e.g. Jira).

### Solutions for prototyping

### Codepen

https://codepen.io/

Small codepens to explain a concept.

* Code is often temporary, to explain a design decision
* Other use case: interface animations coded separately in Codepen
  * Example: https://codepen.io/wolfr/pen/BiGIC

### Bedrock

* Open source static site generator that helps with prototyping
* See: Solutions for component documentation

### Solutions for (component) documentation and template delivery

#### Bedrock

http://bedrock.mono.company 

* Open source static site generator that helps with prototyping
    * Component styleguide
      * Example (out of date, but has similar ideas): http://bedrockinvoicedemo.mono.company/styleguide/
    * Page states feature
      * Read more: https://mono.company/journal/design-practice/how-we-use-bedrock-to-build-interface-prototypes-at-scale/

#### Jekyll

https://jekyllrb.com/

* We have extensive experience with Jekyll, but its usage has declined since we prefer using Bedrock.

#### Fractal

http://fractal.clearleft.com

* Open source tool to document components
    * Adapters for many template languages
* Can be used as a tool to "sync" components between design and FED when Mono is solely delivering designs
* We have not used this yet, but would very much like to, to bridge the gap between what is a component in our Bedrock environment, and what is a component in the “real” dev environment
