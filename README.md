# feedmiles-rules

Public home of [FeedMiles](https://sarathbabu123.github.io/feedmiles-rules/), an Android odometer for your feed.

- `rules.json` and `rules.json.sig` hold the signed rules the app downloads once a day to recognise labels such as "Sponsored" and "Suggested for you". The file has no user data; it is the same for everyone.
- `index.html`, `install.html` and `privacy.html` are the website, served by GitHub Pages.
- APKs are attached to [Releases](https://github.com/sarathbabu123/feedmiles-rules/releases).

Never edit `rules.json` here by hand. It is signed from the main repo with `tools/sign-rules/sign.mjs`, and any change, even line endings, breaks the signature.

FeedMiles is not affiliated with Instagram, Meta, YouTube or Google.
