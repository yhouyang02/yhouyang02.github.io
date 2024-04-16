# Personal Website of Yuheng Ouyang

This if a repo containing sources for my personal website (projects, experiences, notes). The website content is powered by [Jekyll](https://jekyllrb.com/), adapted from the template [Jekyll Garden](https://github.com/Jekyll-Garden/jekyll-garden.github.io.git).

## Viewing from the browser

This website is hosted on GitHub Pages, accessible at [https://yhouyang02.github.io/] or this temporary domain [https://www.yhouyang.me/].

## Rebuilding the project

Fork the project to your local repository and follow the below steps.

### Configuring the environment

1. Install [Ruby](https://www.ruby-lang.org/en/downloads/) (version 2.5.0 or higher) and [RubyGems](https://rubygems.org/pages/download).
   * Check Ruby version using `ruby -v`
   * Check RubyGems version using `gem -v` (should come with Ruby 1.9 or higher)

1. Install [GCC](https://gcc.gnu.org/install/) and [Make](https://www.gnu.org/software/make/).
   * Check GCC version using `gcc -v` and `g++ -v`
   * Check Make version using `make -v`

1. Install Jekyll and Bundler gems using `gem install jekyll bundler`.

1. The public result is built with the following package versions on WSL Ubuntu 22.03.4.
   * Ruby 3.0.2
   * RubyGems 3.3.5
   * GCC 11.4.0
   * Make 4.3

1. For detailed instructions for specific platforms, please visit Jekyll's official manual.
   * [Windows and WSL](https://jekyllrb.com/docs/installation/windows/) (also see Ubuntu below)
     * *Note*: Native Windows is not an officially supported platform by Jekyll.
   * [macOS](https://jekyllrb.com/docs/installation/macos/)
   * [Ubuntu](https://jekyllrb.com/docs/installation/ubuntu/) (also applies to WSL Ubuntu), [FreeBSD](https://jekyllrb.com/docs/installation/freebsd/), and [other Linux](https://jekyllrb.com/docs/installation/other-linux/)

### Project commands

1. `bundle install` to install all missing packages to your local workspace.

1. `bundle exec jekyll serve` to build and start the website on [http://localhost:4000].

<!-- ### Project structures -->
