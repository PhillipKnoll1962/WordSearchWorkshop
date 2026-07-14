THE WORDSEARCH WORKSHOP — UPDATED FILE PACKAGE
=================================================
Packaged: July 2026

WHAT'S IN THIS ZIP
-------------------
All the HTML files for thewordsearchworkshop.com that were touched, reviewed,
or newly built during this session, plus every other page needed to keep the
site complete and testable as a whole.

NEW FILES (didn't exist before):
  - article-crossword-construction.html   (rebuilt from the earlier draft —
    now uses the site's real header/nav/footer and color palette)
  - article-wordsearch-construction.html  (new)
  - article-unscrambler-strategy.html     (new)

UPDATED FILES:
  - wordsearch.html         — BulkWordSelector button/link removed, the
                               false "unsaved changes" warning on page load
                               fixed, site nav header added
  - ai-word-list-generator.html — added a manual "type your own list" option
                               alongside the AI-prompt flow
  - unscrambleword.html     — site nav header added (dictionary logic
                               untouched, as discussed)
  - blog-index.html         — now lists all six articles, grouped under
                               "Craft & Construction" and "Teaching &
                               Classroom Use"

UNCHANGED FILES (included so the package is a complete, testable set):
  about.html, ads.txt, ai-crossword-prompt-generator.html,
  article-geography-lesson.html, article-teaching-vocabulary.html,
  article-wordsearch-vs-crossword.html, bookListPage.html, contact.html,
  index.html, privacy.html, terms.html


NOT INCLUDED — YOU'LL NEED TO KEEP YOUR OWN CURRENT COPIES
-------------------------------------------------------------
  - crossword_builder.html   (never received a working copy of this file's
    content during this session — nothing in this package touches or
    references changing it, so your live version is safe to leave as-is)
  - CNAME                    (same — never received, not needed for any of
    today's changes)
  - Any images/ folder contents (logos, book covers, etc.) — not part of
    this session's work, keep your existing ones


RETIRE THIS FILE FROM YOUR LIVE SITE
----------------------------------------
  - BulkWordSelector.html — no longer linked from anywhere in this package.
    Safe to delete from your server once you've uploaded these files.


HOW TO DEPLOY
--------------
Per your usual workflow: rename each live file before uploading its
replacement (e.g. wordsearch.html -> wordsearch-old.html), so you can roll
back anything that doesn't test out the way you expect.
