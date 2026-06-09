```markdown
# FAQ

## Q: Apakah ini aman untuk SEO?
**A:** Ya. Script hanya membuat link internal yang relevan, tidak membuat link keluar atau spam.

## Q: Bisa dipakai di WordPress?
**A:** Bisa, tapi perlu ubah feed URL dari `/feeds/posts/summary` ke REST API WordPress.

## Q: Kenapa link tidak muncul?
**A:** Cek:
1. Class selector sesuai (`data-ail-selector` atau default `.post .content`)
2. Feed Blogger publik (Settings → Site feed → Allow Blog Feed: Full)
3. Console browser untuk error

## Q: Berapa lama cache disimpan?
**A:** 1 jam. Clear manual dengan `ailClearCache()`.
