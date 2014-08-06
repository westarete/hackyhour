# Hacky Hour

The public website for hackyhour.com, created with [GitHub Pages](https://pages.github.com/).

## Development

For now, it's just a static web page. Resources are linked such that you can just open the file in your browser --
you shouldn't need to set up a host for it. If we want to do anything fancier down the road, then we can 
use [Jekyll](http://jekyllrb.com/), since that's supported out of the box by GitHub Pages too.

## Deployment

You just push to github to deploy. Github follows the convention that the site will be in a `gh-pages` branch, 
which in this case is the only branch in the repo (there is no master). Here is the 
[developer documentation](https://help.github.com/categories/20/articles).

The special `CNAME` file in the project tells GitHub which domain the site should respond for. Then we just point
DNS to the [address that GitHub gave us](https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider).
