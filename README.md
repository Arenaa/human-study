# Human preference study

Anonymous online study: pick which of two regenerations (**A** / **B**) matches the Original better.

**4 parts × 24 trials**, each part balanced **6 + 6 + 6 + 6** across MSCOCO / FLICKR / LEXICA / JD.

**Hub:** https://arenaa.github.io/human-study/

| Part | Link |
|------|------|
| 1 | https://arenaa.github.io/human-study/study.html?p=1 |
| 2 | https://arenaa.github.io/human-study/study.html?p=2 |
| 3 | https://arenaa.github.io/human-study/study.html?p=3 |
| 4 | https://arenaa.github.io/human-study/study.html?p=4 |

## For participants

1. Open a part link (or the hub and choose a part)
2. Click **Start**
3. For each trial, choose **A** or **B**
4. JSON + CSV download automatically
5. Email the files to **mk2524@georgetown.edu**

## For the organizer

```bash
git add -A
git commit -m "Update study"
git push
```

GitHub → **Settings → Pages → Deploy from branch `master` / root**.
