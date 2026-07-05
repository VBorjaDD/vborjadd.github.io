# CV drop-in path

The site already links to a CV from three places (nav bar, hero "Download CV"
button, and the Contact section) at:

```
/cv/Victor-Borja-CV.pdf
```

To make those links resolve, add your CV PDF to this folder with that exact
filename:

```
cv/Victor-Borja-CV.pdf
```

No HTML changes are needed — commit the file here and the existing links
start working. If you'd rather use a different filename, update the three
`href="/cv/Victor-Borja-CV.pdf"` references in `index.html` to match.
