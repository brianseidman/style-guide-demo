# Welcome to the Style Guide Demo

This is a demonstration of the style guide. If this were the actual style guide, it would say something here like that entries in this style guide are copied or adapted from ... and modified based on ... Many examples in this guide are taken directly from those sources ...

And it would continue that entry sources are cited when available ... There might be a logo here, too. And, y'know, some crimson.

<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>

## Table of Contents

### Grammar/Punctuation

- [abbreviations, acronyms](abbreviations,%20acronyms.md)
- [ages](ages.md)
- [alignment, justification](alignment,%20justification.md)
- [ampersand \(&\)](ampersand.md)
- [numbers, numerals](numbers,%20numerals.md)
