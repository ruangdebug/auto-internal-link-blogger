```markdown
# Panduan Konfigurasi

## Config Object Lengkap

```javascript
var CFG = {
  m: 100,              // max feed results
  retry: 2,            // fetch retry count
  retryDelay: 1000,    // initial retry delay (ms)
  t: 0.45,             // similarity threshold
  w: 3,                // min keyword matches
  l: 5,                // max links per article
  p: 10,               // min phrase length
  maxLinkWords: 5,     // max words per anchor
  maxPerParagraph: 2,  // max links per <p>
  earlyParCount: 2,    // early paragraphs count
  earlyParMax: 2,      // max links in early paragraphs
  o: true,             // one link per target
  s: ".post .content", // content selector
  c: "auto-internal-link", // link class
  cacheTTL: 3600000,   // cache TTL (ms)
  cacheKey: "ail_feed_cache"
};
