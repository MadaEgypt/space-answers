---
title: Switching from Questions for Confluence to Space Answers
description: An honest comparison of Questions for Confluence and Space Answers, and how to move a team's Q&A to Space Answers.
---

[Documentation](index.md) · [Demo video](demo.md) · [Switching from Questions for Confluence](switch-from-questions-for-confluence.md) · [Support](support.md) · [Privacy policy](privacy.md) · [Terms](terms.md)

# Switching from Questions for Confluence

Questions for Confluence is Atlassian's own Q&A app. Space Answers is a Q&A app built for one job: a team asks inside its Confluence space, the people who know answer, and the answer is found later by Confluence search. This page compares the two honestly and shows how to move.

## The short version

Switch if your team needs one of these:

- **Search that finds answers, not only question titles.** Each Space Answers question has a Confluence page holding the question and every answer, so Confluence's normal search and quick search find a word that appears only in an answer.
- **Control over who asks and who answers.** A space admin picks the groups that may ask and the groups that may answer, per space. The app checks them on every write.
- **Q&A that lives with the team.** Questions belong to a space, appear in the space sidebar and sit in the space's page tree.

Stay with Questions for Confluence if you depend on voting, topics or one Q&A area for the whole site. Space Answers does not have those today, and it does not take images inside questions (links and code blocks only).

## Side by side

| | Questions for Confluence | Space Answers |
|---|---|---|
| Where questions live | One site-wide Q&A area, organised by topics | Each Confluence space has its own Questions page |
| Confluence search finds words in answers | Users report it searches titles only | Yes: every question has a Confluence page with all its answers |
| Who can ask / who can answer | Not configurable separately | Chosen per space, by group |
| Accepted answer | Yes | Yes, shown first; the asker or a space admin accepts |
| Notifications | Yes | Yes, in the Confluence bell (up to 20 people per space, or the answer groups) |
| Voting on answers | Yes | No |
| Topics / tags | Yes | No |
| Images inside questions | — | No: links and code blocks only |
| Import existing questions | — | Not yet |
| Where data is stored | Atlassian | Your Confluence site only (Forge, *Runs on Atlassian*); no data leaves Atlassian |
| Light and dark theme | — | Follows Confluence automatically |

The search and permission rows reflect what Questions for Confluence users write in its [Marketplace reviews](https://marketplace.atlassian.com/apps/1211644/questions-for-confluence?tab=reviews); check them against your own site.

## How to move a team

1. **Install Space Answers** from the [Atlassian Marketplace](https://rojymart.com/go/docs/switch-install). The 30-day trial is the full app.
2. **Enable one space first.** A space admin opens **Space settings → Integrations → Space Answers** and clicks **Enable in this space**. If enabling is refused, the message names the permission to change ([details](index.md#2-enable-the-app-in-a-space)).
3. **Choose who asks and who answers** on the same page, and who is notified about new questions.
4. **Bring over the questions people still need.** There is no automatic import yet. Most teams re-ask their 10–20 most-viewed questions and paste the accepted answer, which also cleans out outdated ones.
5. **Point people to the new place.** Add a link to the space's Questions page on the space home page. Keep Questions for Confluence installed and read-only for a month so old links still open.
6. **Check search.** Search Confluence for a word that appears only in one of the new answers: the question's page should be the first result.

## Questions about switching

**Can both apps run on the same site?** Yes. They don't share data, so you can move one space at a time.

**What happens to our questions if we stop paying?** They stay in your Confluence site. Without a subscription, people can still read and delete questions and turn the app off in a space, but cannot add or change questions or answers.

**Is anything sent outside Atlassian?** No. Space Answers runs on Atlassian's Forge platform with no servers of its own. See the [privacy policy](privacy.md).

Something missing for your team? [Tell us](support.md): feature requests go into the [public tracker](https://github.com/MadaEgypt/space-answers/issues).
