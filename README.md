# shoulder

A single-page rotator-cuff and scapular rehab reference, built for one person.

Not published yet. To put it on GitHub Pages under `augers-co` (a personal account on the free
plan, so the repo has to be public):

```
gh repo create augers-co/shoulder --public --source=. --push
gh api -X POST repos/augers-co/shoulder/pages -f 'source[branch]=main' -f 'source[path]=/'
```

It would then serve at https://augers-co.github.io/shoulder/

One self-contained `index.html` — no build step, no dependencies, no server. Open the file
directly or serve the directory.

Everything you log — the daily pre-session pain check-in, done-dates, loads, exercises you add,
exercises you hide — lives in this
browser's `localStorage`, on that device only. Nothing is sent anywhere and there is no account.
Use **My data** at the foot of the page to copy, download, or restore it. iOS Safari clears
`localStorage` after about a week of not opening a site, so add the page to your Home Screen and
export it occasionally.

This is a personal reference, not medical advice and not a diagnosis. See "What this isn't" at
the foot of the page.
