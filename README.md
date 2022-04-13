# pris.ly url shortener

## Adding short links

To create the shortened url: `http://pris.ly/internet` pointing to `https://tools.ietf.org/html/rfc3271`

1. Open `_redirects`
2. Add the following line:

```
/internet https://tools.ietf.org/html/rfc3271 301!
```

> The location shouldn't really matter as long as the first part, i.e. `/internet` is unique.

For more information on Netlify redirects: https://docs.netlify.com/routing/redirects/

## Automatic deployment

After merging the PR or after a commit on the main branch, the Netlify deployment will start automatically and will only take a few seconds (~10 seconds) until it's live.
Netlify URL: https://app.netlify.com/sites/prisly/overview
