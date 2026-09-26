# numa-legal

**Retired.** Numa's legal pages now live on numaapps.com, served from the
`junosg/numa-web` repository.

- **Privacy policy (current):** https://numaapps.com/pos/privacy/

`privacy.html` is kept only as a forwarder. The page that stood here named a
contact address that is no longer monitored, and this URL is still reachable
from older Play listings, from search results and from bookmarks — so it
forwards rather than 404s or, worse, keeps answering with stale contact
details.

GitHub Pages cannot issue a 301, so the forward is a meta refresh plus a
canonical link, with a visible link for anyone whose browser honours neither.

Do not add new content here. `.nojekyll` disables Jekyll so the HTML is served
as-is; edit and push to `main` to update the live page.
