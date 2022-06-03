---
title: Lightweight markup language
subtitle: 

# Summary for listings and search engines
summary: What is a lightweight markup language and why is it needed?

# Link this post with a project
projects: []

# Date published
date: '2022-05-12T00:00:00Z'

# Date updated
lastmod: '2022-05-12T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://media.tproger.ru/uploads/2020/12/git_guide_for_beginners-cover-icon-original.png)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---

### Lightweight markup language 

Languages ​​designed to easily and quickly add formatting to text data are called Lightweight markup languages. Features of such languages:

- Minimum of functions.
- A small set of supported tags.
- Easy to learn.
- The source text in this language is read with the same ease as the finished document.
- They are used where a person has to prepare text in a regular text editor (blogs, forums, wikis), or where it is important that a user with a regular text editor can also read the text.

Here are some widely used lightweight markup languages:

- BBCode
- Markdown
- restructured text
- Textile
- Wiki markup
- Various auto-documentation systems

### History

The term "markup" (as a result of the process of the same name, English markup) comes from the English phrase "marking up" ("marking (as a process)", lit. "marking, marking"), taken from the traditional publishing practice of putting special conditional marks on margins and in the text of the manuscript or proofreading before sending it to print. Thus, "markup men" indicated the typeface, style and font size for each part of the text. Nowadays, text markup is handled by editors, proofreaders, graphic designers, and, of course, the authors themselves.

### ΤΕΧ

Unlike ordinary word processors and computer layout systems built on the WYSIWYG principle, in TeX the user only sets the text and its structure, and TeX independently formats the document based on the template chosen by the user, replacing the designer and layout designer. Documents are typed in their own markup language in the form of regular ASCII files containing information about text formatting or displaying images. These files (usually with the extension ".tex") are translated by a special program into ".dvi" (device independent) files, which can be displayed on the screen or printed. DVI files can be converted to PostScript, PDF, or other electronic format with special software.

TeX core is a low-level markup language containing indentation and font change commands. Huge opportunities in TeX are provided by ready-made sets of macros and extensions. The most common extensions to standard TeX (sets of templates, styles, etc.) are LaTeX (pronounced "latex" or "latex") and AMS-TeX. When using the LaTeX extension package, you can turn an overgrown article into a book by changing one word in the source file, inserting a table of contents with one command, and not thinking about numbering sections, theorems, figures. There are many packages for designing chemical formulas (for example, XyMTeX package), diagrams (xypic), creating presentations and business cards, and the like.

##### Usage
TeX can be used for all kinds of text, from short writing to multi-volume books, and TeX was originally created for longer texts and scientific papers. Many large scientific publishers use it for typography or book typesetting. Both the formula set and the font point have special power.

Recently, it has become possible to use TeX to automatically create complex layouts for XML data. Differences in syntax between the two descriptor languages ​​can be overcome with "TeXML". Thus, in the context of XML publishing, TeX can be considered as an alternative to XSL-FO.

##### Fonts
To create fonts, together with TeX, the METAFONT system specially developed by D. Knuth is used, in which fonts are described by programs in a specialized Meta language. PostScript Type 1, TrueType, and OpenType vector fonts can also be used.

### GenCode

The idea of ​​using markup languages ​​in computer word processing was most likely first publicized by William W. Tunnicliffe at a conference in 1967. He himself called his proposal "universal coding" (English "generic coding"). In the 1970s, Tunnicliffe led the development of the GenCode standard for the publishing industry and later became chairman of one of the International Organization for Standardization (ISO) committees that created SGML, the first descriptive markup language. Brian Reid (eng. Brian Reid (computer scientist)) in his dissertation, which he defended in 1980 at Carnegie Mellon University, developed the proposed concept into a practical implementation of descriptive markup.

However, IBM researcher Charles Goldfarb is now commonly referred to as the "father" of markup languages. The basic concept came to him in 1969 while working on a primitive document management system designed for law firms. In the same year, he took part in the creation of the IBM GML language, which was first introduced in 1973.

In 1975, Goldfarb moved from Cambridge, Massachusetts to Silicon Valley, where he became the developer of the IBM Almaden Research Center. There, in 1978, he convinced IBM management to use GML for commercial purposes as part of the company's Document Composition Facility, after which GML was widely used in business for several years.

In 1978, the first developments began, which eventually led to the creation of the SGML standard, based on GML and GenCode. Goldfarb himself later chaired the SGML committee, which was adopted by ISO as a standard in October 1986.

Some early implementations of computer markup languages ​​can be found in UNIX typography utilities such as troff and nroff. They allow you to insert formatting commands into the text of a document to format it according to the requirements of the editor.

The availability of WYSIWYG (what you see is what you get) publishing software has supplanted most of these languages ​​among general users, although serious publishing work still uses markup for specific non-visual structures. text, and WYSIWYG editors now most often save documents in formats based on markup languages.


