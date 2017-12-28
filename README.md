# My Personal Website

dnath.github.io | [devnath.net](http://devnath.net)

author: Dibyendu "Dev" Nath


## Setup

Some pre-requisites:

* brew (for MacOS)
* rvm
* ruby \(> 2.0.0\)
* jekyll (static site generator)

To get list of installed ruby interpreters:

```shell
rvm list
```

TIP: You may need to set a default ruby version with rvm.

Install bundler:

```shell
gem install bundler
```

Ruby gems that need to be installed:

```shell
gem install compass modular-scale sass
```

NOTE: The above ruby gems need to be in very specific (old) versions for gumby
to work properly with compass. It's best to use `bundle install` with the
included `Gemfile`.

## CSS

Customize css or scss in `bower_components/gumby/sass/_custom.scss`.

Useful compass commands:

```shell
compass compile
compass watch
compass compile -s compressed
```

More info at https://gumbyframework.com.

