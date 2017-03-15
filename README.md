# Jekyll Shooot

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs. ([Jekyll Repository](https://github.com/jekyll/jekyll))

**Jekyll Now** makes it easier to create Jekyll blogs, by eliminating a lot of the setup. ([Jekyll Now Repository](https://github.com/barryclark/jekyll-now))

**Jekyll Shooot** makes it easier to create Jekyll portfolios, by adding [Jribbble](https://github.com/tylergaw/jribbble) & [jQuery](https://github.com/jquery/jquery), [Flexboxgrid-sass](https://github.com/hugeinc/flexboxgrid-sass) and more...

### Build a Jekyll-dribbble portfolio in minutes, without touching the command line!

Check it out in [this repository](https://github.com/benkalsky/benkalsky.github.io) and of course, the [portfolio here](http://benkalsky.net).

- You don't need to touch the command line
- You don't need to install/configure ruby, rvm/rbenv, ruby gems :relaxed:
- You don't need to install runtime dependencies like markdown processors, Pygments, etc
- If you're on Windows, this will make setting up Jekyll a lot easier
- It's easy to try out, you can just delete your forked repository if you don't like it

In a few minutes you'll be set up with a minimal, responsive blog like the one below giving you more time to spend on writing epic blog posts!

## Quick Start

### STEP 1: Fork Jekyll Shoot to your User Repository

Fork this repo, then rename the repository to username.github.io.

Your Jekyll blog will often be viewable immediately at <http://username.github.io> (if it's not, you can often force it to build by completing step 2)

### STEP 2: Customize and view your site

Enter your site name, description, avatar and many other options by editing the `_config.yml` file. You can easily turn on Google Analytics tracking, Disqus commenting and social icons here too.

**Don't forget** to enter a Dribbble `Username` and `Client Access Token` to generate the portfolio ([Read more](https://github.com/tylergaw/jribbble#setting-your-apps-client-access-token)).

Making a change to `_config.yml` (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later at <http://username.github.io> - if not, give it ten minutes as GitHub suggests and it'll appear soon

> There are 3 different ways that you can make changes to your blog's files:

> 1. Edit files within your new username.github.io repository in the browser at GitHub.com (shown below).
> 2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
> 3. Clone down your repository and make updates locally, then push them to your GitHub repository.

### STEP 3: Publish your first blog post

Edit `/_posts/2017-3-1-Hello-World.html` to publish your first blog post. This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

> You can add additional posts in the browser on GitHub.com too! Just hit the + icon in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: `YYYY-MM-DD-Fancy-Title.md` or `YYYY-MM-DD-Fancy-Title.html`

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone https://github.com/username/username.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://127.0.0.1:4000/
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

## Questions?

[Open an Issue](https://github.com/benkalsky/jekyll-shooot/issues/new) and let's chat!

## Credits

- [Jekyll](https://github.com/jekyll/jekyll) - Thanks to its creators, contributors and maintainers.
- [Jekyll Now](https://github.com/barryclark/jekyll-now) - Thank you [@barryclark](https://github.com/barryclark), and all your helpers :)
- [Jribbble](https://github.com/tylergaw/jribbble) - Thank you [@tylergaw](https://github.com/tylergaw), great work!
- [Flexboxgrid-sass](https://github.com/hugeinc/flexboxgrid-sass) - [@hugeinc](https://github.com/hugeinc), thanks guys.

## Contributing

Issues and Pull Requests are greatly appreciated. If you've never contributed to an open source project before I'm more than happy to walk you through how to create a pull request.

You can start by [opening an issue](https://github.com/benkalsky/jekyll-shooot/issues/new) describing the problem that you're looking to resolve and we'll go from there.

I want to keep Jekyll Shooot as minimal as possible. Every line of code should be one that's useful to 90% of the people using it. Please bear that in mind when submitting feature requests. If it's not something that most people will use, it probably won't get merged. :guardsman:

[![Analytics](https://ga-beacon.appspot.com/UA-92303047-2/jekyll-shooot/readme?pixel)](https://github.com/igrigorik/ga-beacon)
<meta name="google-site-verification" content="B7fvmk6-3xJBZCljB4t0sQ-tanbME8hlndZnkA_oru4" />
