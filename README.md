# Quarto beamer template with Maastricht University colour scheme

- This is an unofficial template that is not endorsed by the university or the school. 
- The title page background photos were taken by the author and is not endorsed by the university or the school.
- Modified from [`quarto-monash/presentation`](https://github.com/quarto-monash/presentation). 


## Installing


```bash
quarto use template FinYang/um-presentation
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Aspect ratio


To use the wider aspect ratio of 16:9 (default), set
``` yaml
format:
  um-presentation-beamer:
    aspectratio: 169
    titlegraphic: bg-wide.jpg
```

To use the aspect ratio of 4:3, set
``` yaml
format:
  um-presentation-beamer:
    aspectratio: 43
    titlegraphic: bg.jpg
```



## Format options

- `toc: false`
- `titlefontsize: 20pt`
- `fontsize: 14pt`
- `date-format: "D MMMM YYYY"`
- `toc-title: Outline`



## Note



- Removed a few figure placement methods
- No logo yet
