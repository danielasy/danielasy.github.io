# danielasy.github.io

## Requirements

Set up [Jekyll](https://jekyllrb.com/):

```
gem install jekyll bundler
```

## Setup

```
bundle install
```

## Run development server

```
bundle exec jekyll serve
```

## Build and deploy

```
bundle exec jekyll build
git add _site
git commit -m "Update"
git subtree push --prefix _site origin master
```

## License

MIT
