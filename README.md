# Heroku Buildpack for Ruby
![ruby](https://cloud.githubusercontent.com/assets/51578/13712725/3c6b3368-e793-11e5-83c1-728440111358.png)

This is a [Heroku Buildpack](http://devcenter.heroku.com/articles/buildpacks) for Ruby, Rack, and Rails apps. It uses [Bundler](https://bundler.io) for dependency management.

This buildpack requires 64-bit Linux.
 
* Installs CMake, unless already installed.
* Installs OpenCV, unless already installed.
* Continues with the [heroku-buildpack-ruby flow](https://github.com/heroku/heroku-buildpack-ruby#flow)
