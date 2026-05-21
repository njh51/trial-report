# Trial-report Format

A custom Quarto extension that applies standardized Word (`.docx`) formatting and layouts for trial reports.

## Installing

```bash
quarto use template njh51/trial-report
```


This will install the extension and create an example qmd file that you can use as a starting place for your article.

To install this format into a folder you are already working in (without overwriting your existing files), navigate to your folder in the terminal and run:

```bash
quarto add njh51/trial-report
```

This will create a folder named _extensions in your project directory

## Using

Once installed, you can use the custom format by specifying it in the YAML header of your Quarto document (.qmd).

Change the format to trial-report-docx:

```yaml
---
title: "Clinical Trial Results"
author: "Your Name"
format: trial-report-docx
---
```


## Format Options

Format examples

```yaml
  trial-report-docx:
    toc: true
    number-sections: true
    syntax-highlighting: github
    colorlinks: true
    toc-depth: 3
```

## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).