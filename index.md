---
title       : Dit is de titel
subtitle    : Dit is de subtitel
author      : Fred Bosman
job         : RapidSugar BV
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

- Whatever you put after `##` will be the title of the slide
- `---` markt the end of the slide
- `.class #id` are `CSS` attributes you can use to customize the sldie
- Whatever you put between `##` and `---` is up to you!. As long as it is valid R Markdown or 'HTML'

--- .class #id 

## Slide with code


```r
rnorm(6)
```

```
## [1]  0.6405707 -1.6386845 -0.3225463 -0.5413788  0.2509274 -0.6799676
```

--- .class #id 
