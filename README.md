# Using the IBM Blockchain PoT Pages repository

## Overview
This repository gets "built" every time a commit is done against the master branch.  The main content page is index.md, and is designed to not change very often; only when content that is independent of a specific event or location needs to be updated or added should index.md get updated.

When the project gets built, it will scan all the files in the locations directory and if the "location" property is set to true and the "visible" property is set to true that location page will show up in the list of locations on the main page in the form of a link to the location-specific page.

## Adding a location
To add a location:
- create a branch from the `master` branch
- add your location file by copying the template location page `locationtemplate.md`.  Rename it to something unique.
- make sure the `title` property at the top describes your location name
- change the `visible` property to true.
- commit your changes to your branch
- submit a Pull Request to get your branch merged to the `master` branch

When the Pull Request is completed the site will be rebuilt and your location will show up.



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ibm-blockchain-pot/ibm-blockchain-pot.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ibm-blockchain-pot/ibm-blockchain-pot.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
