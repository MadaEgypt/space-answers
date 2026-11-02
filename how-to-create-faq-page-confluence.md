---
title: How to create an FAQ page in Confluence that stays up to date
description: Three ways to build an FAQ in Confluence Cloud with built-in features (one page with expand sections, one page per question with labels, a template), and how to keep it from going stale.
---

[Documentation](index.md) · [Demo video](demo.md) · [Switching from Questions for Confluence](switch-from-questions-for-confluence.md) · [Support](support.md) · [Privacy policy](privacy.md) · [Terms](terms.md)

# How to create an FAQ page in Confluence

An FAQ in Confluence is easy to start and hard to keep alive. The page gets written once, new questions go to chat or email, and six months later half the answers are out of date. Below are three ways to build one with what Confluence Cloud already has, what each is good for, and what keeps any of them current.

## 1. One page, one expand section per question

Best for a short FAQ (up to about 20 questions) that one person maintains.

1. Create a page called **FAQ** in the space, or **[Team] FAQ** if the site has many.
2. For each question, type `/expand` and choose **Expand**. Write the question as the expand's title and the answer inside it.
3. Group questions under headings (*Access*, *Billing*, *Tools*…) and add a **Table of contents** at the top so people can jump to a group.
4. Write each question the way people will search for it: *"How do I connect to the VPN from home?"*, not *"VPN"*.

The catch: Confluence search shows the FAQ page as one result, so a person searching for one question lands at the top of a long page and has to find it.

## 2. One page per question, collected with a label

Best when the FAQ is long, or many people add to it.

1. Create a parent page called **FAQ**.
2. Under it, create one child page per question. The page title is the question; the body is the answer.
3. Give every question page the same label, for example `faq`, plus a topic label such as `faq-vpn`.
4. On the parent page, add the **Content by label** macro and set it to show pages labelled `faq`. The list updates by itself when someone adds a question page.

Now each question is its own search result, with the question as the title, which is what people click. This is the structure that scales.

## 3. A template so new questions look the same

Whichever layout you chose, a page template keeps answers consistent. Create a space template with three headings, **Question**, **Answer** and **Last checked**, and ask people to use it when they add a question. The *Last checked* date is the one that matters: it shows readers how fresh the answer is, and it gives the FAQ owner a list to review.

## Keeping an FAQ current

Every FAQ goes stale for the same reason: the questions are asked somewhere else. People ask in chat, someone answers there, and the FAQ never hears about it. Three habits help:

- **Link, don't retype.** When a question gets asked in chat and the answer is in the FAQ, reply with the link. When it isn't, add it to the FAQ first and then reply with the link.
- **Name an owner per topic** and put the name at the top of each section or parent page.
- **Review by date.** Once a quarter, the owner checks every answer whose *Last checked* date is older than three months.

## When the FAQ should write itself

The habits above work when someone has time for them. The other way is to let people ask in Confluence itself, so the question and the answer are captured where the FAQ lives.

That is what [Space Answers for Confluence](https://rojymart.com/go/docs/faq-article) does (we make it). Each space gets a Questions page; the groups you choose ask and answer; the asker accepts the answer that worked, and it is shown first. Every question gets a normal Confluence page in the space with the question and all its answers, so Confluence search finds any word in an answer, the same as with layout 2 above but without anyone creating the pages by hand.

See also: [how to make Confluence search find your team's answers](confluence-search-find-answers.md) and [Q&A in Confluence: the options](confluence-q-and-a.md).
