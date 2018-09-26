# Jquery::Mask::Plugin

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/jquery/mask/plugin`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jquery-mask-plugin'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jquery-mask-plugin

## Usage

Add to your application.js:

```ruby
    //=require jquery.mask.min.js

    // Example currency mask
    if($('.currency').length) $('.currency').mask('000.000.000.000.000,00', {reverse: true});

```

For more examples access:
https://igorescobar.github.io/jQuery-Mask-Plugin/

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/jquery-mask-plugin.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
