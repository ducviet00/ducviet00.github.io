---
layout: post
title:  "Welcome to Jekyll!"
date:   2025-10-24 15:35:58 +0700
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```python
import torch

# 1. Create Tensors
# Create a 5x3 matrix, uninitialized
x = torch.empty(5, 3)
print("Uninitialized tensor x:")
print(x)
#=> prints 'Hi, Tom' to STDOUT.

def fibonacci_iterative(n_terms):
    """
    Generates the Fibonacci sequence up to n_terms using an iterative approach.
    """
    if n_terms <= 0:
        print("Please enter a positive integer.")
        return
    elif n_terms == 1:
        print("Fibonacci sequence up to 1 term:")
        print(0)
        return

    n1, n2 = 0, 1
    count = 0

    print("Fibonacci sequence:")
    while count < n_terms:
        print(n1, end=" ")
        nth = n1 + n2
        # Update values
        n1 = n2
        n2 = nth
        count += 1
    print() # For a new line after the sequence

# Example usage:
fibonacci_iterative(10)
```


| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
