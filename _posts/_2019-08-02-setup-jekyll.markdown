How to setup a simple Jekyll blog on GitHub

I searched for an easy to use blogging environment, I am a fan of markdown syntax (I use it often when I take notes on my computer) and I don't want to spend any money for this blog (at least not in the beginning). Also choose Jekyll because there are many great plugins e.g. for citations, tagging or many more.

This first blogpost just gives a quick overview on how to set up a Github Page, install Jekyll and get the first version of your Blog running.

1. Create a new GitHub repo and clone that repository to your computer
You can find everything about this over at https://pages.github.com/

2. Create a Jekyll blog in that folder
It's time to install Jekyll now. You need a Ruby runtime environment for that, but that's traight forward to setup: https://jekyllrb.com/docs/installation/

```
gem install bundler jekyll
```

Now we can create our first blog easily. Just navigate to your git repo and execute
```
jekyll new .
```

3. Test your blog locally
You can run this blog locally and access it via http://localhost:4000/
```
bundle install
bundle exec jekyll serve
```
