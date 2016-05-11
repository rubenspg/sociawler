# Sociawler

Sociawler is a DSL created to facilitate the social media crawler on Ruby programs and scripts,
searching and retrieving posts by a given hashtag.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sociawler'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install sociawler

## Usage

### Configuration
In order to use this DSL in your code, after install you need configure.

#### Twitter

#### Instagram

### Commands
To search for given hashtag, you can use one of the following commands of the DSL:

```
posts = twitter '' do
  hashtag: 'rubygem'
  posts: 15
  action :search
end
```

```
posts = instagram '' do
  hashtag: 'rubygem'
  posts: 15
  action :search
end
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/sociawler. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
