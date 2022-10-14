# Changelog

## v.0.2.0

- `gem install bundler:1.16.2`

### Fixed

- `.rvmc` - `rvm use 2.7.1@blog`
- `.ruby-version` 2.7.1
  - Gemfile
    - `ruby ' 2.7.1'`
    - `gem 'rails', '~> 7.0.4'`

### Apply

- :warning: Delete `Gemfile.lock`
- `bundle`
- `rails s`

<!-- Create gemset-->
- `rvm ruby-2.7.1 do rvm gemset create blog`
