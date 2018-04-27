# ruby_gem_hola
Testing out how to build a ruby gem because I'm having an issue with ruby gems on my system and I want to know how they work.

Based on [this guide](http://guides.rubygems.org/make-your-own-gem) from the rubygems website.

### Build Steps

```
gem build hola.gemspec
gem install ./hola-0.0.0.gem
```

### Run steps

```
irb
require 'hola'
Hola.hi
```
