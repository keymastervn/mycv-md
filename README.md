# Pandoc MD resume

pandoc.org/installing.html

Guideline: http://blog.chmd.fr/editing-a-cv-in-markdown-with-pandoc.html

# Render my resume

```
$ pandoc --standalone -c style.css --from markdown --to html -o index.html index.md
```

PDF from html, you need `wkhtmltopdf`

```
$ wkhtmltopdf index.html index.pdf
```

