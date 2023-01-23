
# Philoch Article Template

Quarto template for [Philosophie.ch](https://philosophie.ch) articles. __In development__.

## Creating a New Article

To create a new article using this format:

```bash
quarto use template dialoa/Philoch-template
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add dialoa/Philoch-template
```

Then, add the format to your document options:

```yaml
format:
  philoch-pdf: default
```    

## Options

No options at the moment.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

