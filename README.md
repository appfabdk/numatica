# Numatica Support

Static support site for the Numatica app, served by GitHub Pages at
https://appfabdk.github.io/numatica/

The privacy policy is served at
https://appfabdk.github.io/numatica/privacy/

- `index.html` — support contact, FAQ, screenshots
- `guide/index.html` — copy of the in-app user guide
- `privacy/index.html` — privacy policy

The previous home of this site, `jthiesen/numatica-support`
(https://jthiesen.github.io/numatica-support/), is a legacy copy kept live so
existing links don't break.

## app-ads.txt (AdMob)

AdMob only looks for `app-ads.txt` at the root of the developer website's
domain, so it can't live in this repo (which is served under `/numatica/`).
It is instead served from the org site repo
[appfabdk/appfabdk.github.io](https://github.com/appfabdk/appfabdk.github.io)
at https://appfabdk.github.io/app-ads.txt. That repo's `index.html` redirects
the domain root to this site.

To change the AdMob publisher line, edit `app-ads.txt` in that repo. If the
site ever moves to a custom domain, `app-ads.txt` must move to that domain's
root as well.
