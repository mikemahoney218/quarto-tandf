# Taylor and Francis Template

This is a Quarto template that assists you in creating PDF outputs which closely match the Taylor and Francis template for the rticles package. 

## Creating a New Article

You can use this as a template to create a new article. To do this, use the following command:

```bash
quarto use template mikemahoney218/quarto-tandf
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension mikemahoney218/quarto-tandf
```

## Usage

To use the format, you can use the format names `tandf-pdf` and `tandf-html`. For example:

```bash
quarto render article.qmd --to tandf-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  tandf-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://mike.quarto.pub/demo-taylor-and-francis-template/>.

## In The Wild

Use this template for a paper or a preprint? [Let me know,](https://github.com/mikemahoney218/quarto-tandf/issues/new) and I'll add it to this section!
