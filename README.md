# lisayinyy.github.io

Files served from the root of `https://lisayinyy.github.io/`.

- `robots.txt`: allows crawling of the portfolio and names its sitemap. The portfolio lives at
  [`/floating_island/`](https://lisayinyy.github.io/floating_island/). Crawlers only read
  `robots.txt` at the host root, so it cannot live in the portfolio repository. It also closes
  the data files of `/Programming-Monitor/`, a working site that must not be listed by search
  engines; that site's page is kept out by its own `noindex` mark.
