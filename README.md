# Spree Wishlist - Bootstrap

This fork converts the Spree Wishlist extension to use Bootstrap. Use branch 2-3-bootstrap. 

The Spree Wishlist extension enables multiple wishlists per user, as well as managing those as public (sharable) and private. It also includes the ability to notify a friend via email of a recommended product.

## Installation

Add the following to your `Gemfile`
```ruby
gem 'spree_wishlist', github: 'robin-solutions/spree_wishlist', branch: '2-3-bootstrap'
gem 'spree_email_to_friend', github: 'spree/spree_email_to_friend', branch: 'master'
```

Run
```sh
$ bundle install
$ bundle exec rails g spree_wishlist:install
```

## Contributing

In the spirit of [free software][1], **everyone** is encouraged to help improve this project.

Here are some ways *you* can contribute:

* by using prerelease versions
* by reporting [bugs][2]
* by suggesting new features
* by writing translations
* by writing or editing documentation
* by writing specifications
* by writing code (*no patch is too small*: fix typos, add comments, clean up inconsistent whitespace)
* by refactoring code
* by resolving [issues][2]
* by reviewing patches

Starting point:

* Fork the repo
* Clone your repo
* Run `bundle install`
* Run `bundle exec rake test_app` to create the test application in `spec/test_app`
* You need PhantomJS in your path to pass the specs
* Make your changes
* Ensure specs pass by running `bundle exec rspec spec`
* Submit your pull request

Copyright (c) 2014 [Spree Commerce Inc.][4] and [contributors][5], released under the [New BSD License][3]

[1]: http://www.fsf.org/licensing/essays/free-sw.html
[2]: https://github.com/spree/spree_wishlist/issues
[3]: https://github.com/spree/spree_wishlist/blob/master/LICENSE.md
[4]: https://github.com/spree
[5]: https://github.com/spree/spree_wishlist/graphs/contributors
