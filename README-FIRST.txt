# TrendSpark starter website

A responsive static website starter with a dark neon editorial design, working client-side search/category filters, six sample articles, and About/Contact/Privacy/Disclaimer pages.

## Preview locally
1. Extract the ZIP.
2. Open `index.html` in a browser.

The site uses Google Fonts from a CDN; it will still render with fallback fonts if offline.

## Deploy to Cloudflare Pages (beginner-friendly Direct Upload)
1. Sign in at https://dash.cloudflare.com/
2. Open **Workers & Pages**.
3. Choose **Create application** → **Pages** → **Get started** → **Drag and drop your files** (labels can change).
4. Name the project, e.g. `trendspark-magazine`.
5. Upload the extracted folder contents or a ZIP containing the files. Ensure `index.html` is at the top level, not nested inside another folder.
6. Click **Deploy site**. Cloudflare will provide a `*.pages.dev` URL.
7. Open the URL on desktop and mobile and test every link.

Important: Cloudflare's Direct Upload project cannot later be converted to Git integration. If you want automatic deploys whenever you update code, choose Git integration at project creation instead and connect a GitHub repository. For static HTML, use the repository root as the output directory and a simple/no build step (Cloudflare documents `exit 0` as an option).

Official docs:
- Static HTML: https://developers.cloudflare.com/pages/framework-guides/deploy-anything/
- Direct Upload: https://developers.cloudflare.com/pages/get-started/direct-upload/
- Git integration: https://developers.cloudflare.com/pages/configuration/git-integration/

## Before publishing
- Replace demo content with original, accurate, useful articles. Check facts and cite reputable sources inside articles.
- Customize the About, Contact, Privacy and Disclaimer pages. Set up a real contact channel.
- The newsletter form is only a front-end demo; it does not store or send email. Connect a real mailing-list provider before collecting email addresses.
- Search/filter works only on the sample cards currently on the homepage. Add a real page and unique URL for each new article.
- Replace TrendSpark with your chosen brand, and consider buying a custom domain.
- Add analytics only if you understand the privacy/consent requirements that apply to your audience.

## Google AdSense: safe route
1. Build a useful library of original articles and make sure navigation works.
2. Publish complete About, Contact, Privacy and Disclaimer pages; accurately describe the services and data collection on your site.
3. Get some genuine readers through search, social accounts and relevant communities without spam or purchased traffic.
4. Sign up at https://adsense.google.com/ and submit your website when it is ready.
5. Follow the site's instructions to verify ownership and add the provided AdSense code exactly as instructed.
6. Wait for Google's review. Approval is not guaranteed. After approval, replace the ad placeholder boxes with the actual ad code / Auto ads configuration from your AdSense account.
7. Never click your own ads, ask others to click them, buy fake traffic, use click exchanges, or make ads look like navigation/content. Do not place ads before you have completed Google's setup and policy requirements.

Google's official requirements and policy:
- Eligibility: https://support.google.com/adsense/answer/9724
- Program policies: https://support.google.com/adsense/answer/48182
- Monetization guidance: https://adsense.google.com/intl/en_in/start/resources/monetization-tips-to-optimize-google-adsense/

## How the site can earn
AdSense revenue is not guaranteed and depends on genuine traffic, audience geography, topic, ad demand, viewability and many other factors. There is no reliable fixed income per visitor. Build helpful content, use honest curiosity-driven headlines, improve search visibility, and track which articles satisfy readers. Possible later revenue streams include clearly disclosed sponsorships, affiliate links that genuinely help readers, and your own digital products.

## Headline examples: curious, not deceptive
- “7 everyday tasks AI can help you finish faster”
- “What browser permissions actually let websites access”
- “Why sunlight takes about eight minutes to reach Earth”
- “A 10-minute reset for a scattered day”
Avoid fake urgency, fabricated claims, fake giveaways, and headlines that promise results the article cannot deliver.
