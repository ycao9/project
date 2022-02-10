## Investigation on Latent Dirichlet Allocation

You can use the [editor on GitHub](https://github.com/ycao9/test/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

We investigate both Markov Chain Monte Carlo and variational inference methods for Latent Dirichlet Allocation (LDA), a generative probabilistic topic model for unstructured data such as text. LDA is a generative probabilistic topic model, which means that we treat data as observations resulting from a generative probabilistic process that includes hidden variables, i.e. the structure we're looking for in the data. Topic modeling enables us to meet algorithmic requirements for organizing, comprehending, and annotating documents in accordance with the discovered structure. In the case of text data, hidden variables reflect the thematic structure of a corpus to which we do not have access; we only have access to our observations, which are the collection's documents. Our objective is to infer this hidden structure using posterior inference, that is, to compute the conditional distribution of the hidden variables given our observations. To accomplish this, we will leverage our knowledge from Q1 about inference methods.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ycao9/test/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
