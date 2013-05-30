# WCAGColorContrast

A Ruby port of the Javascript https://github.com/doochik/wcag-color-contrast.

Calculates the contrast ratio between 2 colors, for checking against the WCAG recommended contrast ratio for legibility.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'wcag_color_contrast'
```

And then execute:

```bash
$ bundle
```

Or install it yourself as:

```bash
$ gem install wcag_color_contrast
```

## Usage

Pass 2 rgb colors are strings (3 or 6 characters, case insensitive):

```ruby
require 'wcag_color_contrast'
WCAGColorContrast.new.ratio('999', 'ffffff')
#=> 2.849027755287037
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
