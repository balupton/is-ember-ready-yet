# Can you move to Ember yet?

So Ember 2.0 is out, it's meant to be amazing, or at least [this talk](https://www.youtube.com/watch?v=maAWS8URMJs) says so. So you've been using something else for the past 10 years, what things may you run into migrating to Ember 2.0?


## all-in workflow
The only way mentioned now in the docs of using Ember, is via their ember-cli. No more days of including as little or as much of ember as you need into your existing page. It's now all-in for the ember + ember-cli way, or you're on your own.


## all-in conventions
Want to switch to Ember? You're also going to have to switch your coding standards. The ember-cli will scaffold a new project for you which coding standards are the ember team's coding standards. It would be nice if you could bring your own eslint conventions, and they use esformatter, with [this](https://github.com/flet/eslint-to-esformatter), so that your company can still maintain consistent coding standards accross it's projects, even ember ones.


## jshint only
Want to bring your eslint configuration instead of their jshint configuration? Nope, the ember-cli is locked into their jshint setup.
https://github.com/ember-cli/rfcs/pull/15


## ember 2.0
Want to use the Ember 2.0 (the latest stable version)? Nope, the ember-cli will still install Ember v1.13.
https://github.com/ember-cli/ember-cli/issues/4671


Got more hitches? Are you funnier than this? [Pull request.](https://github.com/balupton/can-you-move-to-ember-yet/edit/master/README.md)