# Air Pollution in Indonesia - Sentiment Classification using BERT
This repository contains the implementation of my sociometrics reseacrh "Public Response to Air Pollution on Indonesian Social Media"

## Keywords
Bahasa Indonesia: polusi;kualitas udara;emsisi karbon;emisi CO2;karhutla (kebakaran lahan dan hutan);nafas;napas;udara;asap;asep;pltu batubara;ISPA (infeksi saluran pernapasan atas);pm2.5;pm2,5;sesak;kabut asap;polusi jakarta;debu; asap pabrik;

## Web scraping tool
[https://apify.com/web.harvester/easy-twitter-search-scraper](url)
```
{
    "includeUserId": true,
    "includeUserInfo": true,
    "profilesDesired": 10,
    "repliesDepth": 0,
    "tweetsDesired": 500,
    "userQueries": [
        "kabut asap",
        "polusi udara",
        "emisi karbon",
        "polusi jakarta",
        "polusi indonesia",
        "udara",
        "asap kendaraan",
        "ISPA",
        "asap pabrik",
        "PLTU batubara",
        "karhutla",
        "debu",
        "#polusi",
        "kualitas udara",
        "asap knalpot",
        "sesak",
        "kabut asap",
        "polusi palembang",
        "#polusijakarta"
    ],
    "excludeImages": false,
    "excludeLinks": false,
    "excludeMedia": false,
    "excludeNativeRetweets": false,
    "excludeNativeVideo": false,
    "excludeNews": false,
    "excludeProVideo": false,
    "excludeQuote": false,
    "excludeReplies": false,
    "excludeSafe": false,
    "excludeVerified": false,
    "excludeVideos": false,
    "images": false,
    "includeUserInfo": true,
    "language": "id",
    "links": false,
    "media": false,
    "nativeRetweets": false,
    "nativeVideo": false,
    "news": false,
    "proVideo": false,
    "quote": false,
    "replies": false,
    "repliesDepth": 10,
    "safe": false,
    "tweetsDesired": 1000,
    "verified": false,
    "videos": false
}
```
## Paper Resource
BERT: [https://arxiv.org/abs/1810.04805](url)
Transformer: [https://arxiv.org/abs/1706.03762](url)
