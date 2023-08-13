---
title: "How to use Quarto embed"
author: "Luis R. Gonzalez"
date: "August 7, 2023"
---

## Using Quarto embed

Testing with markdown and tabulate

{{< embed testing.ipynb#tbl-test >}}

Testing with `.do.markdown()`

{{< embed testing.ipynb#tbl-test-to-markdown-option >}}

Testing using the pandas Styler

{{< embed testing.ipynb#tbl-test-to-markdown-pandas-styler >}}

Testing with `table data-quarto-disable-processing` using the pandas Styler

{{< embed testing.ipynb#tbl-test-to-markdown-option-quarto-disable >}}
