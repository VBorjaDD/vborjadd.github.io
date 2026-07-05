# CV drop-in path

The site links to two CVs — nav bar, hero "Download CV" button, the About
"CV" facts row, and the Contact section — at these two paths:

```
/cv/Victor-Borja-CV-Robotics-TPM.pdf   ← primary (nav + hero CTA): tailored for
                                          robotics / technical product manager roles
/cv/Victor-Borja-CV.pdf                ← secondary: full career CV
```

To make those links resolve, add both PDFs to this folder with these exact
filenames:

```
cv/Victor-Borja-CV-Robotics-TPM.pdf
cv/Victor-Borja-CV.pdf
```

No HTML changes are needed — commit the files here and the existing links
start working. If you'd rather use different filenames, update the matching
`href="/cv/..."` references in `index.html` to match.
