# elliotgmitchell.github.io

This is where my website lives! Published to elliotgmitchell.com

## Setup

To run jekyll website locally:

```
cd docs
bundle install
bundle exec jekyll serve
```

## Steps to update my CV:
1. Update CV on Geisinger PC (or locally)
2. `git -C ~/projects/website/egm_cv pull`
3. `cp ~/projects/website/egm_cv/egm_cv.pdf ~/projects/website/elliotgmitchell.github.io/docs/assets/Elliot\ G\ Mitchell\ CV.pdf`
4. Remember to update "Last updated" date in `/docs/cv.md`

## Steps to publish updates
1. Commit changes and push to `v1` branch
2. Open the repo on [GitHub](https://github.com/elliotgmitchell/elliotgmitchell.github.io)
3. Create and merge a pull request of `v1` into `main`
4. GitHub Actions will automatically deploy the updates to elliotgmitchell.com and elliotgmitchell.github.io


## Notes to self
Website uses the minima theme: https://github.com/jekyll/minima/releases/tag/v2.5.1

Pages not migrated from Wix website:
- /personalized-goals
