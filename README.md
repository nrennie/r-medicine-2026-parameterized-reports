# No more copy and paste! Parameterized plots and reports with R and Quarto

This repository contains the materials for the R/Medicine 2026 conference workshop *No more copy and paste! Parameterized plots and reports with R and Quarto*.

## Abstract

Tired of copying and pasting content from one word document to another each time you write a similar report? Use parameterized reports instead! Parameterized reports allow you write dynamic reports based on input parameters, resulting in more reproducible and quicker reporting. In this workshop, you’ll learn how to write custom `ggplot2` functions to create parameterized plots. You’ll also learn how to create parameterized documents with Quarto, to create multiple versions of HTML documents, Word documents, or PDFs. By the end of the workshop, you’ll be able to create multiple versions of the same report with just one line of code.

This workshop is for you if you make similar PDF reports every month, or you want to create the same plot for different subsets of your data, or you just want some `ggplot2` and Quarto tips!

Some previous experience with `ggplot2` and Quarto would be beneficial, but not essential.

## Software requirements

We’ll be using the following R packages:

* dplyr
* gapminder
* ggplot2
* glue
* plotly
* purrr
* quarto
* tinytable

You should also have Quarto CLI installed, alongside R itself.

## Outline of workshop

* Welcome and intro (5 mins)
* Part 1: Parameterized plots with ggplot2 (25 mins)
  * Slides
  * Live Demo (How to write a function that makes a plot)
  * Exercise
  * Exercise solutions and questions
* Part 2: Parameterized reports with Quarto(25 mins)
  * Slides
  * Live Demo (how to add parameters to documents and pass them into document and functions)
  * Exercise
  * Exercise solutions and questions
* 10 minute break
* Part 3: Parameterized text with Quarto (25 mins)
  * Slides
  * Live Demo (inline code to write sentences, and how to add it to document metadata and figure options)
  * Exercise
  * Exercise solutions and questions
* Part 4: Rendering multiple reports (25 mins)
  * Slides
  * Live Demo (Using purrr and quarto package to create many reports)
  * Exercise
  * Exercise solutions and questions
* 10 minute break
* Part 5: Conditional content (25 mins)
  * Slides
  * Live Demo (conditional content based on output format and/or parameters)
  * Exercise
  * Exercise solutions and questions
* Part 6: Parameterized report sections (25 mins)
  * Slides
  * Live Demo (one report with many similar plots or sections)
  * Exercise
  * Exercise solutions and questions
* Wrap up (5 mins)

