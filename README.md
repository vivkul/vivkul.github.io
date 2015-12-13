#vivkul.github.io
================

Jekyll powered "app" for [my webpage](http://vivkul.github.io/). This is very modular. All you need to change in the data in _config.yaml and you can have your own awesome web home. I used the information from `up` and `left` repos to hack this.

------------


## Installation

- Install Jekyll: `gem install jekyll`
- [Fork this repository](https://github.com/vivkul/vivkul.github.io/fork)
- Clone it: `git clone https://github.com/YOUR-USER/YOUR-USER.github.io`
- Run the jekyll server: `jekyll serve` . Alternative: `gem install bundler` and `bundle exec jekyll serve --watch` to see on localhost:4000



## Customization

Next you'll want to change a few things. Most of them can be changed directly in
[_config.yml](https://github.com/vivkul/vivkul.github.io/blob/master/_config.yml). That's
where we'll pull your name, Twitter username, and things like that.

There's a few other places that you'll want to change, too:

- [navbar.html](https://github.com/vivkul/vivkul.github.io/blob/master/_includes/navbar.html):
  Change it to edit navbar
- [CNAME](https://github.com/vivkul/vivkul.github.io/blob/master/CNAME): If you're using
  this on GitHub Pages with a custom domain name, you'll want to change this
  to be the domain you're going to use. All that should be in here is a
  domain name on the first line and nothing else (like: `example.com`).
- [favicon.ico](https://github.com/vivkul/vivkul.github.io/blob/master/favicon.ico): This
  is for use as the icon in your browser's
  address bar. You should change it to whatever you'd like.
- The YAML info at the top of index.html and blog.html (the key:value pair text between the two --- lines )
- Create your _posts/X files honoring the naming convention.
- You don't have to look at any of the html. Ignore it fully in the first try.

## Deployment

You should deploy with [GitHub Pages](http://pages.github.com)- it's just easier.

All you should have to do is rename your repository on GitHub to be
`YOUR-USER.github.com` where YOUR_USER is your username. Since everything is on the `gh-pages` branch, you
should be able to see your new site at <http://YOUR-USER.github.io>.

## Licensing

This is [MIT](https://github.com/vivkul/vivkul.github.io/blob/master/LICENSE) with no
added caveats, so feel free to use this on your site without linking back to
me or using a disclaimer or anything silly like that.
