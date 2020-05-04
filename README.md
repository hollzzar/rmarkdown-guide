# [R Markdown for Psychology Graduate Students](https://hollzzar.github.io/rmarkdown-guide/)

This guide started as a [tutorial](https://github.com/hollzzar/markdown-tutorial) that I developed for my fellow cognitive psychology graduate students at Penn State. R Markdown is a highly useful platform for combining data processing, analysis, and presentation, but there's a steep learning curve for developing proficiency beyond the basic skills. If we're all stressed and short on time, how can I make R Markdown approachable and efficient to use for graduate students like me?

I hope this guide provides a solid jumping off point for other students who are curious about using R Markdown in graduate school. Here, you'll find the tips and tricks that I've compiled from countless hours of rifling through Stack Overflow and troubleshooting broken code. If you think this guide is missing anything or is unclear at any point, I encourage you to reach out and let me know.

I've included an overview of each of the chapters below. The chapters are generally organized by complexity: they start with basic information on the parts of an R Markdown document, work through the important features, and end with information on troubleshooting. While the guide assumes a basic level of comfort or familiarity with R, I also included supplementary materials on R itself at the very end, as well as practice documents for exploring R Markdown and `tidyr`.

## [Welcome](https://hollzzar.github.io/rmarkdown-guide/index.html)

What is R Markdown and why should you use it?

## [Parts of a document](https://hollzzar.github.io/rmarkdown-guide/intro.html)

1. YAML header
2. Markdown
3. Code chunks

## [Outputs](https://hollzzar.github.io/rmarkdown-guide/output.html)

R Markdown can transform plain text and code into several different document formats. There are also multiple ways to **Knit** or `render` the output.

## [Templates](https://hollzzar.github.io/rmarkdown-guide/template.html)

1. Built-in templates
2. Templates from R packages
3. User-defined templates

## [Content](https://hollzzar.github.io/rmarkdown-guide/content.html)

The content of an R Markdown document includes the markdown text itself, as well as output from code chunks. Code chunks can output data, graphs, tables, and images. You can also reference variables from code chunks in markdown text.

## [Formatting](https://hollzzar.github.io/rmarkdown-guide/format.html)

There are many ways to customize the formatting of an R Markdown document. In the YAML header, you can specify different parameter options or reference external documents. You can also edit templates directly in certain cases. For local formatting, you can include inline code in the markdown sections.

## [Organization](https://hollzzar.github.io/rmarkdown-guide/organization.html)

Keeping documents and scripts organized is critical for reducing headaches (literal and figurative) when working on large R Markdown projects. This chapter covers *child* R Markdown documents and *sourcing* R scripts to keep your content organized.

## [Troubleshooting](https://hollzzar.github.io/rmarkdown-guide/trouble.html)

We've all been there. How can you avoid or handle warnings, errors, and other issues in R Markdown?

## [Supplementary materials](https://hollzzar.github.io/rmarkdown-guide/supplement.html)

The supplementary materials are broken down into Beginner and Intermediate R. [Beginner R](https://hollzzar.github.io/rmarkdown-guide/supplement.html#beginner-r) covers basic R functionality, reading/loading in data, the `tidyr` philosophy, and using `tidyr` functions for transparent coding. [Intermediate R](https://hollzzar.github.io/rmarkdown-guide/supplement.html#intermediate-r) focuses on free-response text, dynamic variables, and other functions. The [practice materials for R Markdown and R](https://hollzzar.github.io/rmarkdown-guide/supplement.html#practice-materials) are also linked at the end.
