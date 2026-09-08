# harshg97.github.io

Personal site — a single self-contained `index.html`, no build step.

| File | |
|---|---|
| `index.html` | the whole site: markup, styles and a small theme toggle |
| `profilephoto.jpeg` | portrait used in the hero and as the social preview image |
| `Harsh_Gupta_Resume.pdf` | copy of the current AI/ML resume, linked from the hero |

## Editing

Open `index.html` and edit it. To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Pushing to `main` publishes to https://harshg97.github.io within a minute or two.

## Updating the resume

The resume is built in the separate `resume` repo. To refresh the copy here:

```bash
cp ../resume/Harsh_Gupta_Resume_AI.pdf Harsh_Gupta_Resume.pdf
git commit -am "Update resume" && git push
```
