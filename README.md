# Hacky Hour

The public website for <http://hackyhour.com>, created with [GitHub Pages](https://pages.github.com/).

## Development

For now, it's just a static web page. We started out by generating a page from GitHub's "Architect" theme, and
then we edited the HTML and CSS for our own content. 

The resources are linked such that you can just open the file in your browser while you're developing --
you shouldn't need to set up a host for it. 

If we want to do anything fancier than a static page down the road, then we can 
use [Jekyll](http://jekyllrb.com/), since that's supported out of the box by GitHub Pages too.

Here the [management console for our Google Maps API key](https://code.google.com/apis/console/b/0/?noredirect&pli=1#project:585355924652:overview) 
(only accessible to a few users @westarete.com).

## Deployment

You just push to github to deploy. Github follows the convention that the site will be in a `gh-pages` branch, 
which in this case is the only branch in the repo (there is no master). Here is the 
[developer documentation](https://help.github.com/categories/20/articles).

The special `CNAME` file in the project tells GitHub which domain the site should respond for. Then we just point
DNS to the [address that GitHub gave us](https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider).
