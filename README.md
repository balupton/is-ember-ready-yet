# Can you move to Ember yet?

So Ember 2.0 is out, it's meant to be amazing, or at least [this talk](https://www.youtube.com/watch?v=maAWS8URMJs) says so. So you've been using something else for the past 10 years, what things may you run into migrating to Ember 2.0?


## pain


### all-in workflow
The only way that the docs say you can use Ember now, is via their ember-cli. No more days of including as little or as much of ember as you need into your existing page. It's now all-in for the ember + ember-cli way, or you're on your own.


### all-in conventions
Want to switch to Ember? You're also going to have to switch your coding standards. The ember-cli will scaffold a new project for you which coding standards are the ember team's coding standards. It would be nice if you could supply your own eslint file to the cli, which could use [esformatter](https://github.com/millermedeiros/esformatter/) with [this](https://github.com/flet/eslint-to-esformatter), so that your company can still maintain consistent coding standards accross its projects, even ember ones.


### jshint only
Want to bring your eslint configuration instead of their jshint configuration? Nope, the ember-cli is locked into their jshint setup. https://github.com/ember-cli/rfcs/pull/15


### release sync
Want to use the Ember 2.0 (the latest stable version)? Nope, despite the Ember 2.0 docs, the ember-cli will still install Ember v1.13. https://github.com/ember-cli/ember-cli/issues/4671


### size
It's never mentioned, but in case you were wondering, Ember 2.0 is 107.46KB gzipped (420.34KB uncompressed). Would be nice if this was mentioned somewhere on the website.


## praise

### [emberaddons.com](http://www.emberaddons.com)
Want something ember related? This website has it all. It's not quite [Polymer Elements](https://elements.polymer-project.org) yet (which offers inline demos and docs), but it's quick links to demo pages gets you by. The quality rating of each item is also super nifty.



## feedback

Got more hitches? Are you funnier than this? [Pull request.](https://github.com/balupton/can-you-move-to-ember-yet/edit/master/README.md)

## why

The goal of this repo is to provide exposure for common pain points that newcommers are facing with adopting ember. With increased exposure, hopefully newcomers will know what they are up against, and be better equipped to deal with the pain points when they face them, as well as help the ember community resolve these issues that newcommers face. Ember is awesome, give it a go.
