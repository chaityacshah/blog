---
layout: default
title: How I made the blog?
---

In this post, I'll be sharing how I made this blog. I hope it helps others in quickly setting up their own `{your-username}.github.io` page. To start with, you can clone my repository using  
`git clone https://github.com/chaityacshah/chaityacshah.github.io.git`.  
The Gemfile contains information necessary for developing GitHub Pages. You can refer several websites (for instance, [GitHub Docs](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)) if you want to learn more about Jekyll and developing GitHub Pages using Jekyll.

After cloning my repository, you can make necessary modifications in the following files:
1. index.md
2. \_config.yml

`index.md` is the homepage. `\_config.ml` contains site-wide information like your email id, title, etc. Once you're done, push the changes to your `{your-username}.github.io` repository.

Careful readers will notice a link in `index.md`- [https://chaityacshah.github.io/blog]. There's no `blog` folder in my github.io repository. [Blog](https://github.com/chaityacshah/blog) is another public repository that I have created. Again, clone it using:  
`git clone https://github.com/chaityacshah/blog.git`  
and make necessary changes in `index.md` and `\_config.yml` files. Start 'committing' your stories in the `_posts` folder. Make sure you push your work to `gh-pages` branch of a repository named `blog` (or some other repository that you created. Make sure to put the corresponding link in index.md file of your github.io repository). Use the following commands to create a new branch `gh-pages` and push to `gh-pages` branch.

```
git checkout -b gh-pages
git push origin gh-pages
```

For testing this project locally,
```
cd ##your-github.io-folder
bundle exec jekyll serve
```

Feel free to reach out to me in case you need any help in setting up your GitHub Pages. Also, I would be happy to read the stories you share.

Acknowledgments: [Tyler Brown](http://tbonza.github.io/)

{% include twitter_plug.html %}