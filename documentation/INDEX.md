# what do we want to achieve

we want to create a webpage that helps other people to understand HTML,
CSS and JS the way we learned it.

## structure

these are the pages we want to create. all pages with green background
are the first ones to be created.

we create them by **copying** the `_template.html` file e.g. to
`about_us.html`.

```plantuml
@startwbs

!theme materia
title sitemap

*[#lightgreen] start\n index.html
**[#lightgreen] HTML\n html/index.html
*** html basics\n html/basics.html
*** html more\n html/more.html
**[#lightgreen] CSS\n css/index.html
*** css basics\n css/basics.html
*** css more\n css/more.html
** javascript
*** js history
*** js syntax
**[#lightgreen] legal / imprint\n legal.html
**[#lightgreen] about us\n about_us.html

@endwbs
```

# design

the design should be part of the `_template.html`.

so there should be a `header`, a `footer` and a `main`. the main navigation should be in a `nav` tag.
