# The Digital Defense Company's Website

Website for The Digital Defense Company.

This website is heavily inspired by [L'Ami du peuple](https://en.wikipedia.org/wiki/L%27Ami_du_peuple), a newspaper written by [Jean-Paul Marat](https://en.wikipedia.org/wiki/Jean-Paul_Marat) during the French Revolution, in which he was a j vocal advocate for the rights of man and liberty.

## Installation

```bash
brew install rbenv ruby-build
echo 'eval "$(rbenv init - zsh)"' >> ~/.zshrc
source ~/.zshrc
```

Then install desired ruby version:

```bash
rbenv install 3.2.3
```

Finally, either set installed `ruby` in global, or local scope, or both:

```bash
rbenv global 3.2.3
rbenv local 3.2.3
ruby -v
ruby 3.2.3
```

Finally install `bundler` gem:

```bash
gem install bundler
bundle -v
```

Now we are good to go!

## Usage

1. Adapt the `_config.yml` file
2. Replace/Delete the posts
3. Change `about.md`
4. Change or add your links in the `nav.yml` file located in the `_data` folder
5. Replace the `favicon.ico`
6. Customise the `404.md` page in the root directory
6. Run `bundle exec jekyll serve --watch`
7. Enlighten the masses!

> Unlike Marat's pamphlets the theme is fully responsive.

Plugins:

Marat includes the following plugins.

* [jekyll-roman](https://github.com/paulrobertlloyd/jekyll-roman)
* [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
