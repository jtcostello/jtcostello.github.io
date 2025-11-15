# Local Preview Commands

## Quick Start

Make sure rbenv is initialized (add to `~/.zshrc` if needed):
```bash
eval "$(rbenv init -)"
```

Then run:
```bash
bundle exec jekyll serve
```

Or with live reload:
```bash
bundle exec jekyll serve --livereload
```

Site will be available at: `http://localhost:4000`

## Notes

- Ruby version is managed by rbenv (3.1.2) - see `.ruby-version`
- If you get errors, make sure you're using rbenv Ruby, not system Ruby
- Check Ruby version: `ruby --version` (should show 3.1.2, not 2.6.x)

