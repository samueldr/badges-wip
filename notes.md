# Notes

## Font

 * Vegur (`nixpkgs.vegur`)

## What to replace?

 * `%NAME0%` → full names
 * `%NICK0%` → nicknames
 * `%IMAGE0%` → avatars

The indices go from one (1) to ten (10); yes, I'm mad.


## Making sure the image is 1024x1024

```
convert in.png -thumbnail 1024x1024^ -gravity center -extent 1024x1024 out.1024.png
```

## Exporting

```
inkscape --export-pdf=out.pdf badge-herma-9011.svg
```
