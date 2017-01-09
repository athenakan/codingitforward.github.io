# CodingItForward.github.io

## Running the site

Ensure you have Ruby 2.1.0 or higher; to check your Ruby version, do:

```
ruby --version
```

Then run:

```
gem install bundler
bundle config build.nokogiri --use-system-libraries
bundle install
```

If you get an error with a gem called `nokogiri`, [try this guide](http://stackoverflow.com/questions/19643153/error-to-install-nokogiri-on-osx-10-9-maverick).
