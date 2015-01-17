
# respect

[![Build Status](https://travis-ci.org/brynbellomy/Respect.svg?branch=master)](https://travis-ci.org/brynbellomy/Respect)
[![GitHub tag](https://img.shields.io/github/tag/brynbellomy/Respect.svg?style=flat)]()

Testing helpers (for use with [Quick](https://github.com/Quick/Quick) and [Nimble](https://github.com/Quick/Nimble))

(Better README coming soon.)

# install

### Carthage

In your `Cartfile`:

```ruby
github "brynbellomy/Respect"
github "Quick/Quick"
github "Quick/Nimble"
```

In your project root, run:

```sh
$ carthage update
```


### CocoaPods

For the time being, only the pre-release beta of CocoaPods 0.36 is capable of working with Swift code.  To install it, use `gem install cocoapods --pre`.

In your `Podfile`:

```ruby
target :MyTestTarget do
    pod 'Respect', :git => 'https://github.com/brynbellomy/Respect.git'
    pod 'Quick', :git => 'https://github.com/Quick/Quick.git'
    pod 'Nimble', :git => 'https://github.com/Quick/Nimble.git'
end

```

In your project root, run:

```sh
$ pod install
```



# contributors / authors


bryn austin bellomy < <bryn.bellomy@gmail.com> >
