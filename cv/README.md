# Chan Hur — CV source

`fancy-rover.tex` is the updated source of the CV linked from the homepage.
It is adapted from the main template in the supplied `CV.zip`.
The homepage and this CV were reconciled on October 19, 2026.

Compile with **XeLaTeX** (twice) or **Tectonic**, using the fonts
**Liberation Sans** and **Noto Sans CJK KR**. The Korean font is needed for
patent titles and an award. For example, from this directory:

```sh
tectonic fancy-rover.tex
```

Review the generated PDF, then copy it to `../assets/files/CV_Chan Hur.pdf`.
That existing path is used by the homepage's CV link.

Conventions:

- List workshops within International Conferences, retaining the workshop venue.
- Mark the specified co-first authors with `*` only.
- Keep the accepted and under-review PopupBench records separate.
- Do not add private submission links to under-review records.
- Keep publication details, patent status, and employment dates consistent with the homepage.
