---
title: "Confluence search not working? Six things to check"
description: Confluence Cloud search seems to find only page titles, or misses a page you know exists. The usual causes, from quick search versus full search to permissions and exact phrases, and how to fix each.
---

[Documentation](index.md) · [Demo video](demo.md) · [Switching from Questions for Confluence](switch-from-questions-for-confluence.md) · [Support](support.md) · [Privacy policy](privacy.md) · [Terms](terms.md)

# Confluence search not working? Six things to check

Most "Confluence search is broken" reports turn out to be one of a handful of causes. Go through them in order; the first one is by far the most common.

## 1. You're looking at quick search, not the full search

The results that appear while you type are quick search: they lean on titles and recently viewed pages. A word that appears only inside a page often won't show there. **Press Enter** to open the full search results page, which searches page content too.

This one comes up often enough on the Atlassian Community that it's worth checking before anything else.

## 2. A filter is narrowing the results

On the full search page, look at the filters. A **titles only** option, a space filter, a contributor filter or a date range left over from an earlier search will hide pages that match. Clear the filters and search again.

## 3. You don't have permission to see the page

Search only shows what you're allowed to view. If a page has restrictions, or sits in a space you don't have access to, it won't appear for you even though it appears for a colleague. Ask the page owner or a space admin, or search from an account that can open the page directly.

## 4. The words don't match closely enough

To find an exact phrase, put it in double quotes: `"error 401 on login"`. Without quotes Confluence matches the words separately, which helps for loose questions and hurts for error messages and product codes. Try both.

## 5. The page is archived or brand new

Archived content can be left out of results unless you include it with the search filters. And a page created a moment ago may take a short while to be searchable.

## 6. The answer lives in a comment

A good answer often sits in a comment on a page called something like *Team notes*. Search may find it, but the result shows the page title, and nobody clicks a page called *Team notes* when looking for a VPN fix. [Why answers get lost in Confluence search, and how to fix it](confluence-search-find-answers.md).

## If it's questions and answers you can't find

When the thing people search for most is answers to questions that were asked before, the fix is structural: give every question its own page, titled with the question, holding all its answers. You can do it by hand ([one page per question, collected with a label](how-to-create-faq-page-confluence.md)), or let an app keep those pages for you.

[Space Answers for Confluence](https://rojymart.com/go/docs/search-fix-article) does that (we make it): each space gets a Questions page, the groups you choose ask and answer, and every question gets a normal Confluence page with all its answers, so the full search finds any word in an answer.
