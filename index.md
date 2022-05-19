## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/NoahGWood/TunerHelper/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NoahGWood/TunerHelper/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


<div class="container">
    <div id="repo-cards" class="columns is-multiline list">
        {% for repo_data in site.data.all_repos %}
            {% assign repo = repo_data[1] %}
            <div class="column is-3-widescreen is-4-desktop is-6-tablet is-8-mobile">
                DERP
            </div>
        {% endfor %}
    </div>
</div>

<script> var options = { valueNames: [ { name: 'list-name', attr: 'data-name' } ] }; var userList = new List('repos', options); </script> 
