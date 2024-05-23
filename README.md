# columbia-point-boston

*Jekyll website for the Columbia Point Boston Project @ [Boston College](https://bc.edu)*

By Emily Coello

## About

For Bostonians in the 1960s and 1970s, the words “Columbia Point” probably would have instantly brought images of criminality, poverty, and the epitome of a local urban crisis. The sensationalized stories of racial conflicts, gangs, and a general urban wasteland - removed from the rest of Boston - proved to be a great story, and perhaps even fueled the fire for the busing crisis a few years later. Despite this, the Columbia Point Housing Project was not Boston’s only declining public housing project. South Boston’s D Street Housing Project was named the worst public housing by the Boston Housing Authority (BHA) - 40% of all maintenance costs were spent on directly repairing vandalism, and “at any given time, 300 to 400 windows need to be replaced.” The media however, focused on Columbia Point and its strong racial demographics.

The Columbia Point Housing Project for a long time has lived under a doomed and entirely negative perspective. The tenants of Columbia Point, who for the majority of its existence were low-income minorities, were very quickly seen as exacerbators of an ever-worsening conditions and that what was happening at Columbia Point, if not nipped in the butt, would be a microcosm of cities failing all across the country. This project aims to follow the peninsula through the decades and see the strengths and failures of urban renewal, and ultimately explore who is the most affected. 

## Local Development

* Follow [this guide](https://jekyllrb.com/docs/installation/) to install Ruby and Jekyll
* Install [Node](https://nodejs.org/en)
* `git clone` this repo and then `cd` inside the directory
* Comment out the `url` and `baseurl` lines of `_config.yml` when working locally
* Install Ruby dependencies by running `bundle install`
* Install Node dependencies by running `npm install`
* Run the server with `bundle exec jekyll serve`

## How to Make Changes

**To set attribution**

``` bash
README.md # this file, make sure to change with your name in the credits
CITATION.cff # the citation file, make sure to include your project name and author(s) names. Use OrcIDs if you have them
package.json # the npm package file, include the project title and author information (again)
_config.yml # the Jekyll config file, which controls how the page is put together, include project name, author names, project locations, and footer messages
```

**To change the theme**

``` bash
_sass/theme-settings.scss # edit this file to change theme colors, fonts, and the sizes of the headers/footers
_sass/custom-style.scss # edit this file to add your CSS (or SCSS) to the site. CSS here will override other files
_sass/theme.scss # advanced, contains the code for the theme itself, edit to customize the theme directly
```

**To change the site structure (the nav menu)**

```bash
_config.yml # the Jekyll config file, edit the section titled nav-menu. Note that you can nest menus using a submenu attribute
_pages/ # where you create individual site pages (either .html or .md). As you change the _config.yml you should create new files here, or rename/delete existing ones, to match _config.yml
```

**To use built-in TailwindCSS**

```bash
https://tailwindcss.com/docs # tailwind is already installed, consult the docs to look up how to use it for things like flex layout, margins, alignment, and more
```

``` html
<!-- example of a tailwindcss element that goes to width 100% and also centers the text inside-->
<div class="w-full text-center">Some text</div>
```

## Acknowledgements

Jekyll & Tailwind Setup based on [TailPages](https://github.com/harrywang/tailpages) by [Harry Wang](https://harrywang.me/) (Chinese: 王建楠)