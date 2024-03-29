# rochesterton.github.io

Website for the annual [_Fr. Leo Hetzler Chesterton Conference_ in Rochester, NY](https://www.rochesterton.com/)

## Contributing (the easy way)

1. When you change a file on GitHub, make sure you've selected `Create a new branch for this commit and start a pull request`
2. From the Pull Request page, preview your changes by clicking on the `Details` link opposite `deploy/netlify — Deploy Preview ready!`
3. If you need to make more changes, click on the branch name under the PR title, then keep editing from there
    - like `edbrannin-patch-1` in "edbrannin wants to merge 1 commit into master from edbrannin-patch-1")
    - In this case, no need to repeat Step 1, since you're not on `master`
4. Merge, and it will go live in a couple minutes
5. Bother Ed if something goes wrong

## Contributing (local development)

1. Install [nodejs](https://nodejs.org/)
2. Clone this repo
3. In a terminal, run `npm ci` to download the stuff that builds the site
4. Make your changes
5. Run `npm start` to preview your changes
6. When you're happy with what you've done:
    1. Check out a branch: `git checkout -b short-description-of-change`
    2. Push: `git push`
    3. Make a PR (there will be a link in the `git push` output, or a button on the main page for this repo)
7. There will be a preview link in the PR
8. If it looks good, merge
9. Bother Ed if something goes wrong

## To Do

- [x] Convert to 11ty: https://www.11ty.io/docs/
- [x] Host on Netlify or Google PAges w/ GitHub Actions
- [ ] Add Netlify CMS
- [ ] Add "Notice" section to layout (for between-conference notes)
    - [ ] Add a global attribute to set/unset?
    - [ ] Make it a blog, latest post (optionally) "featured"?
- [ ] Add after-conference front page
