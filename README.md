# jorobledo.github.io

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fjorobledo.github.io&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Hits&edge_flat=false)](https://hits.seeyoufarm.com)

## Local compilation

Needs ruby, jekyll, and bundler . On Mac

```bash
brew install ruby
gem install jekyll bundler
```

If no Gemfile

```bash
bundle init
```

Add this to Gemfile
```bash
gem "github-pages", group: :jekyll_plugins
```

Then run 

```bash
bundle install
```

and finally

```bash
bundle exec jekyll serve
```