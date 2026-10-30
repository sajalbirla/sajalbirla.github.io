# Root GitHub Pages support

Publish these files from the main branch root of `sajalbirla/sajalbirla.github.io`.
This serves host-level crawler configuration and Google ownership verification.
The portfolio remains at https://sajalbirla.github.io/sajal-portfolio/.

- `/robots.txt` allows crawling and lists the existing portfolio sitemap.
- `/googleb66a47c3371cebd5.html` is the Google verification file supplied by the owner.
- `/index.html` links to the portfolio and uses noindex to avoid a competing landing page.

After deployment, add a URL-prefix property for https://sajalbirla.github.io/
in Google Search Console and verify with the HTML-file method. Confirm Google
requests the same filename; replace the file if Google supplies a different token.
Select the root property for Settings > robots.txt and Crawl stats. Data appears
when Google crawls and processes the host; deploying these files does not generate
crawl statistics or guarantee indexing.
