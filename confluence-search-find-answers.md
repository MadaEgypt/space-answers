---
title: How to make Confluence search find the answers to your team's questions
description: Why Q&A answers often don't show up in Confluence search, three ways to fix it with plain Confluence, and when a Q&A app helps.
---

[Documentation](index.md) · [Demo video](demo.md) · [Switching from Questions for Confluence](switch-from-questions-for-confluence.md) · [Support](support.md) · [Privacy policy](privacy.md) · [Terms](terms.md)

# How to make Confluence search find your team's answers

A question gets asked, someone answers it well, and three months later the next person can't find it. In Confluence this usually has one of three causes. Each has a fix that needs no app.

## 1. The answer is in a comment, not in the page

Confluence search indexes page comments, but results show the page title, and a long comment thread on a page called "Team notes" rarely looks like the answer to anything.

**Fix:** when a question is settled, copy the answer into the page body under a heading that repeats the question in the words people will search with, for example *"How do I connect to the VPN from home?"* rather than *"VPN"*.

## 2. Q&A lives in a content type search doesn't show by default

Some Q&A tools store questions as their own Confluence content type. Confluence indexes them, but the normal search results and quick search often show only pages and blog posts unless the reader adds a **Type** filter. People who don't know the filter conclude the answer doesn't exist.

**Fix:** in **Search → Filters → Type**, include the Q&A type, and tell your team. Or keep a normal page per question (see the next section), which shows up with no filter.

## 3. The question title is all that's indexed

Some tools match only the question's title. A question titled "Error on login" will never be found by someone searching the actual error message that appears only in the answer.

**Fix:** write titles as the full question, and paste exact error messages into the question text. Check: search for a word that appears only in an answer. If the question doesn't come up, your tool searches titles only.

## A page per question, kept up to date

The fixes above depend on people remembering to do them. The structural fix is to give every question a normal Confluence page that holds the question and all its answers, updated whenever an answer changes. Then Confluence's normal search finds any word in any answer, with no filter and no habit change.

That's how [Space Answers for Confluence](https://rojymart.com/go/docs/search-article) works (we make it): each space gets a Questions page, the groups you choose ask and answer, the asker accepts the answer that worked, and every question gets a page in the space's tree that only the app can edit. Confluence search then finds the answer by any word in it. If you're coming from Atlassian's Questions for Confluence, see [what's different and how to switch](switch-from-questions-for-confluence.md).
