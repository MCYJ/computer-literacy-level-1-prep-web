# 컴퓨터활용능력 1급 Prep website context

## Identity

- Service: KOR-0007
- Android package / iOS bundle: `app.mcyj.examprep.kor0007`
- Repository: `MCYJ/computer-literacy-level-1-prep-web`
- Base path: `/computer-literacy-level-1-prep-web`
- Source app directory is read-only for website work.

## Live publication verified — 2026-09-18

- Google Play public product page returned HTTP 200 for the exact Android package.
- Apple lookup returned public track ID `6797070786` for the exact iOS bundle in the KR storefront.
- Exact Store URLs are active in the website; subscription pricing is intentionally not duplicated because live localized prices may change.

## Official exam facts verified — 2026-09-18

- Authority: 대한상공회의소 자격평가사업단 (KCCI).
- Level 1 written: computer fundamentals, spreadsheet fundamentals and database fundamentals; 60 multiple-choice items; 60 minutes.
- Level 1 practical: spreadsheet and database work; 90 minutes, 45 minutes per subject.
- Written pass: at least 40/100 in each subject and 60/100 overall average.
- Practical pass: at least 70/100 in both spreadsheet and database.
- Current listed fees: KRW 20,500 written and KRW 25,000 practical; users are directed to recheck before payment.
- Current 2024–2026 software: Microsoft Office LTSC Professional Plus 2021. The 2027–2029 specification is already published for future application.
- Written pass validity: two full years from the pass announcement; the practical test date must fall within that window.
- KCCI says live question-bank items are not published; the app and website use independent preparation content.

## Design and content rules

- Korean-primary, English-secondary because the exam itself is Korean while international residents may need an English orientation.
- Spreadsheet-cell and database-record visual thesis; dusty teal palette inherited from the app without copying generic templates.
- `word-break: keep-all` applies to all body and control text; long URLs retain emergency wrapping.
- 12 substantive guides per locale plus FAQ, privacy, terms, support and contact.
- Independent-product disclaimer appears throughout; no endorsement, secured-question or pass-guarantee claims.

## Production deployment — 2026-09-18

- Public repository: https://github.com/MCYJ/computer-literacy-level-1-prep-web
- Production URL: https://mcyj.github.io/computer-literacy-level-1-prep-web/
- Initial GitHub Pages deployment run `35354190614` passed.
- Generated 38 indexable routes: 19 Korean and 19 English; total output is 40 HTML files including root redirect and custom 404.
- All 38 sitemap routes and required assets returned HTTP 200; an unknown route returned HTTP 404.
- Production CSS contains the required `word-break: keep-all` rule.
- Exact live Store identity was rechecked after deployment: Google Play HTTP 200; Apple lookup result count 1 with track ID `6797070786`.
- 2026-09-18: Normalized Google Play and App Store controls to a shared 194×75 frame while preserving official artwork ratios; local build and check passed.

## 2026-10-23 — SEO technical improvements

- Added dependency-free post-build SEO validation and enhancement: valid reciprocal language alternates, page-preserving language switching, source-backed Article identities/citations, BreadcrumbList, social text metadata, noindex on the utility 404, and priority for existing above-fold app imagery.
- Removed unverified structured-data offers where present. Preserved existing official-source verification dates, visible study content, app artwork, keep-all and equal marketplace badge frames.
- Public repository instructions were treated only as methodology; no external skill, tool, tracking, account connection, or scheduled action was installed.
