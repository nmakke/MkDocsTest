

??? note "success"

    -    Content.
    -    Content2.
  
  <details>
    <summary><u>nested</u> <b>stuff</b> (<i>click to expand</i>)</summary>
    <!-- have to be followed by an empty line! -->

A bit more than normal indentation is necessary to get the nesting correct,
* list
* with
    * nested
    * items
        ```java
        // including code
        ```
  * blocks
* and continued non-nested

  </details>


<details>
  <summary>stuff with *mark* **down** in `summary` doesn't work any more, use HTML <i>italics</i> and <b>bold</b> instead in <code>&lt;summary&gt;</code> (<i>click to expand</i>)</summary>
  <!-- have to be followed by an empty line! -->

## *formatted* **heading** with [a](link)
```java
code block
```

  <details>
    <summary><u>nested</u> <b>stuff</b> (<i>click to expand</i>)</summary>
    <!-- have to be followed by an empty line! -->

A bit more than normal indentation is necessary to get the nesting correct,
 1. list
 1. with
    1. nested
    1. items
        ```java
        // including code
        ```
    1. blocks
 1. and continued non-nested

  </details>
</details>


# Welcome to My Docs

This is the front page of My Docs.

## Sub

This is another section.
Example of mathematical formulas

# MathJax Test Page

When \(a \ne 0\), there are two solutions to \(ax^2 + bx + c = 0\) and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

Given a data set **$\mathcal{D} =(x_i,f(x_i))_{i=1}^{n}$**, the goal is to learn the function **$f(x)$** such that **$y_i = f(x_i)$** for all data points.


<!--
...

{{ read_csv('./FeynmanEquations.csv') }}

...
-->
