# My Website

This is the source for my website. It is created using Jekyll

## Getting Started

### Ubuntu

Follow the Ubuntu install steps for installing Jekyll on
[the Jekyll website](https://jekyllrb.com/docs/installation/ubuntu/).

### Windows

Follow the Windows install steps for installing Jekyll on
[the Jekyll website](https://jekyllrb.com/docs/installation/windows/), but
instead of manually downloading Ruby, you can install it using `winget` by
running `winget install RubyInstallerTeam.RubyWithDevKit.X.Y` where `X` and `Y`
are the major and minor version numbers to install

## Updating Gems

Update system rubygems with the command `gem update --system`

## Bundler

Bundler is similar to pipenv. It allows creating lockfiles (called gemfiles) for
the set of necessary packages for the project. It additionally allows executing
programs included in the pacages.

Useful command for bundle with jekyll

* `bundle install`: Install packages specified in lockfile
* `bundle update`: Update packages specified in lockfile to match what is in gemfile
* `bundle exec`: Execute commands
  * `bundle exec jekyll`: Execute jekyll
    * `bundle exec jekyll build`: Build website
    * `bundle exec jekyll serve`: Host website for development. (I recommend to use the `--livereload` flag)
