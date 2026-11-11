# Follow a story through the Bible (extended data)

An interactive tool for tracing stories across the Old and New Testaments. Open `index.html` in a browser, or use the hosted copy. It is a static page: no server, no build step, and your journeys are saved in your own browser.

## Using it

- **Start:** "New journey" lets you search for a story (450 events such as "Birth of Jesus"), a passage ("Luke 2"), or a person or place.
- **Next steps:** the flowchart shows up to six next passages, each with the reason it is linked. The faded boxes to the right are one step further on. Click one to jump two steps at once.
- **Direction:** the chips at the top limit the kind of link: quotations and echoes, parallels, cross-references, same story, same people, same place. The scope menu limits where steps can come from.
- **Names and places:** underlined words in the passage are clickable. "Follow" ranks passages that mention that person or place.
- **History rail:** click any earlier step to rewind. Choosing a different next step keeps the old branch as a dashed fork you can return to. The left arrow key also steps back.
- **Sharing:** "Copy path code" copies a short code for the current path. Anyone using the same tool can click "Open shared path" and paste it.

## Journeys

The **Journeys** button opens a workspace for everything you have saved: search, tags, sort, duplicate and merge; five views of each journey (tree, arcs, map, timeline, printable study guide); 14 ready-made journeys; Markdown, print and PDF export; and backup and restore of your whole library.

## What the extended data adds

This is the same tool as the plain version, with more links from the `bible-connections` dataset (CC BY 4.0, by Michael Spears): quotations, allusions and parallels that were found by matching words in the King James text and the Greek New Testament, then reviewed.

| | Plain version | This version |
|---|---|---|
| Quotation links | 382 | 592 |
| Parallel links | 2,334 | 2,803 |

- **Echoes:** a link from the New Testament to the Old that the dataset calls an allusion, and that no other source lists, shows as "echoes this passage" or "echoed by this passage", and ranks a little below a quotation.
- **Parallels inside one testament:** Gospel parallels, Kings and Chronicles, Colossians and Ephesians, repeated scenes in Revelation, and so on. A high-confidence connection counts 3, a medium one 2 and a low one 1, added to the weight from the UBS parallels.
- **Ranges:** where a connection covers several passages on both sides, they are lined up by position, not linked pair by pair.
- **Same passages as the plain version,** so path codes and journey backups work in both. Journeys in this version are saved separately.

**Every new link is marked `proposed`.** They were reviewed by an AI assistant (Claude), not by a person, so expect some that a careful reader would drop, mostly ritual and genealogical repetition.

## Disagreeing with a link

Every step has a **⚑ Disagree with a link, or suggest one** button (and a small ⚑ on each next-step card). It opens a short form: pick the link, say what is wrong (not a real link, wrong type, wrong direction, wrong passage), give your reason, or switch to "Suggest a missing link". **Open on GitHub** opens a new issue on this repository with the report filled in, including the link's id when the link comes from the bible-connections dataset. **Copy report** copies the same text if you would rather send it another way. Nothing is sent from the page: GitHub asks you to sign in and you press Submit there.

Only links from the bible-connections dataset can be changed by this project. Cross-references, UBS parallels, events, people and places come from other projects; reports about them are welcome and will be passed on.

## Known limits

- Links are only as good as the source data. Some are broad (cross-references) and some are missing.
- Dates follow one scholar's chronology.
- The map uses a coarse 110m coastline, so the Sea of Galilee and the Dead Sea are not drawn.
- Ready-made journeys were chosen by hand. Where the data has no link between two steps they are labelled "curated link".
- Names are tagged by the source. Pronouns and titles are not clickable.
- Journeys are stored per browser; share them with path codes or the backup file.

## License and credits

Released under CC BY-SA 4.0 (see `LICENSE`). The data is adapted from Theographic, the UBS Parallel Passages, OpenBible.info, kalvesmaki.com and Natural Earth. See `DATA_SOURCES.md` for what each provides, its license, and what was changed.
