# Can you move to Ember yet?

Ember 2.0 is out, it's meant to be amazing, or at least [this talk](https://www.youtube.com/watch?v=maAWS8URMJs) says so. You've been using something else for the past 10 years, what things may you run into migrating to Ember 2.0?


## dealbreakers

### release sync
Want to use the Ember 2.0 (the latest stable version)? Nope, despite the Ember 2.0 docs, the ember-cli will still install Ember v1.13. https://github.com/ember-cli/ember-cli/issues/4671

The release sync between Ember, Ember Data, and Ember Core - all critical components of Ember, has never been resolved for the many years they've been around - they are never stable, documented, and released together.

As far as I'm concerned, this is the main reason why ember is vapourware. [original tweet](https://twitter.com/balupton/status/538911146317606912)


### all-in conventions
Want to switch to Ember? You're also going to have to switch your coding standards. The ember-cli will scaffold a new project for you which coding standards are the ember team's coding standards. It would be nice if you could supply your own eslint file to the cli, which could use [esformatter](https://github.com/millermedeiros/esformatter/) with [this](https://github.com/flet/eslint-to-esformatter), so that your company can still maintain consistent coding standards accross its projects, even ember ones.


### jshint only
Want to bring your eslint configuration instead of their jshint configuration? Nope, the ember-cli is locked into their jshint setup. https://github.com/ember-cli/rfcs/pull/15





## annoyances

### all-in workflow
The only way that the docs say you can use Ember now, is via their ember-cli. No more days of including as little or as much of ember as you need into your existing page. It's now all-in for the ember + ember-cli way, or you're on your own. It would be nice if some documentation about selective usage of Ember was around, perhaps as a supplement to the install guide.

### size
It's never mentioned, but in case you were wondering, Ember 2.0 is 107.46KB gzipped — would be nice if this was mentioned somewhere on the website. In comparison, Polymer 1.0 is 40.02KB gzipped, React 0.13.3 is 35.36KB gzipped.


## praise

### [emberaddons.com](http://www.emberaddons.com)
Want something ember related? This website has it all. It's not quite [Polymer Elements](https://elements.polymer-project.org) yet (which offers inline demos and docs), but its quick links to demo pages gets you by. The quality rating of each item is also super nifty. Beats [React Parts](http://react.parts/web).



## feedback

Got more hitches? Are you funnier than this? [Pull request.](https://github.com/balupton/can-you-move-to-ember-yet/edit/master/README.md)

Have you tried to use Ember but gave up? [Add your name](https://github.com/balupton/can-you-move-to-ember-yet/edit/master/README.md):

- [balupton](https://github.com/balupton)


## why

The goal of this repo is to provide exposure for common pain points that newcommers are facing with adopting ember. With increased exposure, hopefully newcomers will know what they are up against, and be better equipped to deal with the pain points when they face them, as well as help the ember community resolve these issues that newcommers face. Ember is awesome, give it a go.
