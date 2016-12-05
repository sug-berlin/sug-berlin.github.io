# SailfishOS Meetup Berlin

Tis repository contains the [SailfishOS User Group Berlin website](https://sug-berlin.github.io). The page is generated using [Jekyll](https://jekyllrb.com).

## Installation and preparation

The following needs to be done in order to create a testable, local running version of the page: 

1. Clone this repository: `git clone git@github.com:sug-berlin/sug-berlin.github.io.git`
2. Switch to cloned working directory: `cd sug-berlin.github.io`
3. Install Jekyll and other dependencies from the GitHub pages gem: `bundler install`
4. (Optional) Serve page locally: `bundler exec jekyll serve`

this description is based on [this description](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)


## Update and publish the page


### Blogpost

You could simply use the github website to do the following steps. 

1. Create a file in the [_posts directory](https://github.com/sug-berlin/sug-berlin.github.io/tree/master/_posts): (naming scheme: `yyyy-mm-dd-blogpost-title.md`)
  - Find a [template for blogposts here](https://github.com/sug-berlin/sug-berlin.github.io/blob/master/template-new-post.md)
2. If you do nothave write access to the repository create a pull request. Otherwise just save the new file in the _post directory.

The updated page now is available at the [SailfishOS User Group Berlin Website](https://sug-berlin.github.io) and will provide a link to the blogpost you created in the *Posts* section.

### Main Page

The *Main Page* is the root page shown to everyone visiting https://sug-berlin.github.io

- to be continued...

### Pages

It is possible to create Sub Pages for several topics in order to include and link them. This section describes how to create these kind of pages.

- to be continued...

## Contributing

We are always looking for ideas, findings and people who would like to join our meetups or projects. If you would like to add content to the page just follow the description obove and create a pull request or open an [issue](https://github.com/sug-berlin/sug-berlin.github.io/issues).
