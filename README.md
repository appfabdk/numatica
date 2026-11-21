# Numatica Support

Static support site for the Numatica app, served by GitHub Pages at
https://jthiesen.github.io/numatica-support/

The privacy policy is served at
https://jthiesen.github.io/numatica-support/privacy/

- `index.html` — support contact, FAQ, screenshots
- `guide/index.html` — copy of the in-app user guide
- `privacy/index.html` — privacy policy

## app-ads.txt (AdMob)

AdMob only looks for `app-ads.txt` at the root of the developer website's
domain, so it can't live in this repo (which is served under
`/numatica-support/`). It is instead served from the GitHub user-site repo
[jthiesen/jthiesen.github.io](https://github.com/jthiesen/jthiesen.github.io)
at https://jthiesen.github.io/app-ads.txt. That repo's `index.html` redirects
the domain root to this support site.

To change the AdMob publisher line, edit `app-ads.txt` in that repo. If the
site ever moves to a custom domain, `app-ads.txt` must move to that domain's
root as well.
