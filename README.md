# ECGJSON

Currently-incomplete Scryfall-like search engine for Eternal Card Game, utilizes heavy image hotlinking (sorry, developer of EternalWarcry).

## Questions (non-frequent)

**Q:** What's complete?

**A:** You can use it as an image gallery for Eternal cards, and can view if a card is in Expedition or its weight in the Eternal Draft Pack (it's not very useful because you can't narrow its search down or sort it).

---

**Q:** What's incomplete?

**A:** Two functions related to parsing shorthand terms in `index.html`, one function related to returning the index of each card from a search query, and one function related to simplifying the list of results given a list of arrays of indexes and the logic gates between them. Additionally, cards' "Unit Types" are missing from the `eternal-cards.json`. The JSON is sourced from [EternalWarcry](https://eternalwarcry.com/cards/download), and the missing data can be found at that location (I have no idea why it disappeared).

---

**Q:** When will it be complete?

**A:** When I feel like it.

---

**Q:** How can I use it?

**A:** Download and run `index.html` on your computer.

---

**Q:** Why is the entirety of the program a single HTML file?

**A:** Just because React looks good on your resume doesn't mean you should use it for anything.

