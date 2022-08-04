## Old libraries for old Rubies on new Macs.

This is a [Homebrew Tap](https://github.com/Homebrew/brew/blob/master/docs/brew-tap.md#taps-third-party-repositories) with some old libraries updated for M1 compatibility to help you install [old Ruby versions](https://github.com/basecamp/ruby-dev) on current macOS.

These are for development use only and are well past their end of life and security support. ☠️

### OpenSSL 1.0 for Ruby 1.8 through 2.4

```
brew install basecamp/dev/openssl@1.0
RUBY_CONFIGURE_OPTS="--with-openssl-dir=$(brew --prefix basecamp/dev/openssl@1.0)" rbenv install [old-ruby-version]
```
