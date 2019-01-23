# parse-a-changelog

This gem uses the [treetop parsing DSL](https://github.com/cjheath/treetop) to
parse changelogs that use the [Keep a Changelog](https://keepachangelog.com)
standard.

## Usage

Add `parse-a-changelog` to your Gemfile and `bundle install` or install directly with:

```
gem install parse-a-changelog
```

The gem can then be used via CLI:

```
parse path/to/changelog
```

Or it can be used directly in your Ruby code:

```
result = ParseAChangelog::parse("path/to/changelog")
```

# Development

We welcome contributions of all kinds to `parse-a-changelog`. See our [contributing guide](CONTRIBUTING.md).

# License

The parse-a-changelog gem is licensed under Apache License 2.0 - see [`LICENSE.md`](LICENSE.md) for more details.