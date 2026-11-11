# PROVE human preference study

Anonymous online study: pick which of two regenerations (**A** / **B**) matches the Original better (100 trials).

**Live page:** after GitHub Pages is enabled →  
`https://Arenaa.github.io/prove-human-study/`

## For participants

1. Open the page link
2. Click **Start**
3. For each trial, choose **A** or **B**
4. At the end, JSON + CSV files download automatically
5. Email the files to **mk2524@georgetown.edu**

## For the organizer (publish / update)

```bash
# from this folder
git add -A
git commit -m "Update study"
git push
```

GitHub → **Settings → Pages → Deploy from branch `main` / root**.

Add an empty `.nojekyll` file (already included) so `stimuli/` paths work.
