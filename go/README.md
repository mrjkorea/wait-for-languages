# Short links (UTM tracking)

These paths redirect to the signup landing page with channel-specific `utm_source` values.

**Base site:** https://mrjkorea.github.io/wait-for-languages/

| Channel   | Short URL |
|-----------|-----------|
| Instagram | https://mrjkorea.github.io/wait-for-languages/go/ig/ |
| TikTok    | https://mrjkorea.github.io/wait-for-languages/go/tt/ |
| YouTube   | https://mrjkorea.github.io/wait-for-languages/go/yt/ |
| Naver     | https://mrjkorea.github.io/wait-for-languages/go/naver/ |
| Cafe      | https://mrjkorea.github.io/wait-for-languages/go/cafe/ |
| Reddit    | https://mrjkorea.github.io/wait-for-languages/go/reddit/ |
| X         | https://mrjkorea.github.io/wait-for-languages/go/x/ |
| Threads   | https://mrjkorea.github.io/wait-for-languages/go/threads/ |
| Pinterest | https://mrjkorea.github.io/wait-for-languages/go/pin/ |
| Other     | https://mrjkorea.github.io/wait-for-languages/go/other/ |

Each redirect adds:

- `utm_source` = channel slug (`ig`, `tt`, `yt`, …)
- `utm_medium` = `social`
- `utm_campaign` = `wfl_signup`

The landing page forwards any `utm_*` query parameters to the Kit signup URL when visitors click **Get the free weekly tip**.
