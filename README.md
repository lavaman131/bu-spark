# bu-spark.github.io
The start of Spark! Tech Resources

# Developing locally

## Install ruby environment manager

https://github.com/rbenv/rbenv#installation

## Install compatible version of ruby
```bash
rbenv install 3.1.4
```

```bash
# run this in bu-spark to set the correct ruby version
rbenv local 3.1.4
```

## Install the jekyll and bundler gems

```bash
gem install jekyll bundler
```

## Install all project dependencies

```bash
bundle install
```

## Build the site and make it available on a local server
```bash
# use --livereload to reflect changes live
bundle exec jekyll serve --livereload
```