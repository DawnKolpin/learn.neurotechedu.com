# [www.learn.neurotechedu.com](http://learn.neurotechedu.com/)

NeurotechEDU is an open-source project designed to promote collaboration and user-generated content.
The idea is that if you are not finding something that should be part of our resources you can go ahead and make it and upload it to our page.

The project is built with the help of:

 * [Foundation](http://foundation.zurb.com/)
 * [Jekyll](http://jekyllrb.com/)
 * [Feeling Responsive Jekyll theme](https://phlow.github.io/feeling-responsive/) by Phlow

Github is necessary if you wish to contribute to NeurotechEDU. [You can learn about Github here.](https://guides.github.com/activities/hello-world/)


##Contributing

We have set up the contribution process to be as simple as possible so that people who don’t have much experience programming are still able to contribute.

+ There are two ways to do so:
  - By editing a new page directly on Github and requesting a commit
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ By cloning this repository, instally jekyll and making the page locally (this option allows for previews).

    With either, once done, you push a commit to us and once a pproaved you content becomes part of the wbesite.

Both options require a combination of HTML and Markdown are used, but for the purpose of contributing you only need to know the Markdown format which you can learn about here. Unlike HTML, Markdown is very sensitive about spacing. Elements such as lists might need a blank line before and after the element in order to work properly.

## Jekyll Setup for Mac OS and Linux

The website uses [Jekyll](http://jekyllrb.com/), a static website generator written in Ruby.
You need to have Version 2.0.0 or higher of Ruby and the package manager Bundler.
(The package manager is used to make sure you use exactly the same versions of software as GitHub Pages.)
After checking out the repository, please run:

```
$ bundle install

```

to install Jekyll and the software it depends on.
You may consult [Using Jekyll with Pages](https://help.github.com/articles/using-jekyll-with-pages/) for further instructions.

You will also need [Python 3](http://python.org/) with
[PyYAML](https://pypi.python.org/pypi/PyYAML/) available in order to
re-generate the [data files](#details) the site depends on.

## Jekyll on Windows

Installing Jekyll on Windows is somewhat different. [You can learn about it here.](https://jekyllrb.com/docs/windows/)

## Fundamental changes to default template

The Neurotech EDU logo HTML/CSS was changed for the header type "image_fullwidth". The affected files are "masthead.html", "navigation.html" and "layout.scss". The logo used to be positioned on top of the header image.

If you simply want to change the logo image, that is done from config.yml

## Making a contribution


In order to parcitpate, we have set up the following architecture:

Your contribution should come in the form of a page.
Examplaes include : headsets, getting started.

To start making a page, you can clone the repostiroy:

to be in the for of a new page, under the /pages folder.

```
/pages
    /template.md
```

To start, copy the template.md file and start editing in markdown.

