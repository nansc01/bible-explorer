# Bible Explorer

An interactive Bible library in a single web page. The Library tab maps all 66 books, and each built passage gets its own hands-on tab:

| Tab | Passage | What you can do |
|---|---|---|
| In the Beginning | Genesis 1–3 | Speak light into the dark, watch creation build day by day, name the animals, search the garden |
| Through the Sea | Exodus 12–14 | Mark the doorframe, pack for the road, follow the route, cross the sea |
| No King in Israel | Judges 1–21 | The whole book: the repeating cycle, twelve judges charted, Deborah, Gideon's 300, Samson, and the dark ending |
| For Such a Time | Esther 1–10 | The whole book: the empire at a glance, the cast lot, the relay through Hathach, a sleepless night, six reversals and the days of Purim |
| The Third Day | Luke 22–24 | The upper room, Peter by the fire, the three courts, roll the stone, walk to Emmaus |
| The Word Became Flesh | John 1–3 | Question John the Baptist, fill the six jars at Cana, the night wind with Nicodemus |
| Wind and Fire | Acts 1–2 | The ascension, casting lots, fifteen nations hearing in their own language, three thousand added |
| No Condemnation | Romans 3–8 | Paul's argument as seven steps, from "all under sin" to a love nothing can break |
| All Things New | Revelation 21–22 | The city coming down, its gates and jewels, the river and tree of life, back to Eden |

## The heart of each story

Every passage tab opens with a lesson layer:

- **One core word and lesson** for the whole passage (Esther: *Surrender*, Exodus: *Deliverance*, Romans: *Grace* and so on).
- **The shape of the story**, a chart of hope rising and falling across the seven scenes, with the turning point marked. Tap a scene to read its takeaway and jump to it.
- **Character cores**: each key person's defining trait and moment (with the verse), marked *Follow this*, *Beware* or *Learn from both sides*, plus what it means for us.
- **A takeaway in every scene**, and **Take it home** reflection questions before the quiz.

Lessons are interpretation and are labelled that way; the moments they rest on are cited.

## How it works

- One file, `index.html`, with no build step and no outside libraries. Open it in any browser, or serve it with GitHub Pages.
- Every claim has a gold reference. Tapping it shows the verse and the page in the NIV PDF it was checked against.
- Text is retold in plain words, with only short direct quotes (a signature line per key character). Labels mark what is an illustration, an observation, a calculation or an interpretation.
- Remembers where you stopped, has light and dark modes and adjustable text size, and works on phones.

## Publishing with GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`. The site appears at `https://nansc01.github.io/bible-explorer/`.

## Adding a passage

Pick chapters in the Library tab, copy the request it writes, and ask Claude to add it as a new tab.

Scripture paraphrases are based on the New International Version (NIV).
